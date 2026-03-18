# params 
 {'predict_dates': [{'start': '2026-03-18', 'end': '2026-03-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260317_14 943415086406659812 (Recorders: 5/5)

	Recorder: c3abd792ac91455c8b3791c563bad812

		Model: {'id': 'c3abd792ac91455c8b3791c563bad812', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.021, 'Rank ICIR': 0.118}, 'data_train_vec': ['2021-03-17', '2024-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.118', 'weight': '0.024'}

	Recorder: 78ce6c134e9f4e6cbbc41e288a748c72

		Model: {'id': '78ce6c134e9f4e6cbbc41e288a748c72', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.08, 'Rank IC': 0.02, 'Rank ICIR': 0.105}, 'data_train_vec': ['2022-03-17', '2025-03-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.105', 'weight': '0.022'}

	Recorder: 3bcbc79956fc409cb0c319a26f3f12c2

		Model: {'id': '3bcbc79956fc409cb0c319a26f3f12c2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.072, 'Rank IC': 0.025, 'Rank ICIR': 0.147}, 'data_train_vec': ['2023-03-17', '2025-06-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.147', 'weight': '0.030'}

	Recorder: acaa82e171614ebba32eb8eb899febaf

		Model: {'id': 'acaa82e171614ebba32eb8eb899febaf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.025, 'Rank ICIR': 0.236}, 'data_train_vec': ['2024-03-17', '2025-09-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.236', 'weight': '0.049'}

	Recorder: c0b5730afe9742afad7095de186db07c

		Model: {'id': 'c0b5730afe9742afad7095de186db07c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.162, 'Rank IC': 0.11, 'Rank ICIR': 0.738}, 'data_train_vec': ['2025-03-17', '2025-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.738', 'weight': '0.152'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260317_14 731726242520896455 (Recorders: 1/5)

	Recorder: 2b245ba9d9c2447c9836e1765b922448

		Model: {'id': '2b245ba9d9c2447c9836e1765b922448', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.223, 'Rank IC': 0.04, 'Rank ICIR': 0.308}, 'data_train_vec': ['2024-03-17', '2025-09-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.308', 'weight': '0.064'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260317_12 325812596008727400 (Recorders: 4/5)

	Recorder: 7f1d84337713455c8ba3c8123f6bf5bf

		Model: {'id': '7f1d84337713455c8ba3c8123f6bf5bf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.091, 'Rank IC': 0.033, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-03-17', '2024-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.185', 'weight': '0.038'}

	Recorder: 079e94d1945f4c1cbe303f287e53da3f

		Model: {'id': '079e94d1945f4c1cbe303f287e53da3f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.033, 'Rank IC': 0.025, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-03-17', '2025-03-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.139', 'weight': '0.029'}

	Recorder: c29cd594b1f341389dcecf762c0981a2

		Model: {'id': 'c29cd594b1f341389dcecf762c0981a2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.254, 'Rank IC': 0.03, 'Rank ICIR': 0.301}, 'data_train_vec': ['2024-03-17', '2025-09-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.301', 'weight': '0.062'}

	Recorder: b825f740be994c908b60e5d014800038

		Model: {'id': 'b825f740be994c908b60e5d014800038', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.191, 'Rank IC': 0.058, 'Rank ICIR': 0.528}, 'data_train_vec': ['2025-03-17', '2025-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.528', 'weight': '0.109'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260317_12 896260384917616719 (Recorders: 5/5)

	Recorder: 4aadae30b597480b9c517b8b909c6c0e

		Model: {'id': '4aadae30b597480b9c517b8b909c6c0e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.153, 'Rank IC': 0.025, 'Rank ICIR': 0.214}, 'data_train_vec': ['2021-03-17', '2024-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.214', 'weight': '0.044'}

	Recorder: 10a152f164cb4a0ab761447920e96d36

		Model: {'id': '10a152f164cb4a0ab761447920e96d36', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.142, 'Rank IC': 0.024, 'Rank ICIR': 0.212}, 'data_train_vec': ['2022-03-17', '2025-03-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.212', 'weight': '0.044'}

	Recorder: f1de8842a23d431b8925acf17d8586e9

		Model: {'id': 'f1de8842a23d431b8925acf17d8586e9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.107, 'Rank IC': 0.032, 'Rank ICIR': 0.273}, 'data_train_vec': ['2023-03-17', '2025-06-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.273', 'weight': '0.056'}

	Recorder: 6234957e3abb4fab99beefc8369962d8

		Model: {'id': '6234957e3abb4fab99beefc8369962d8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.132, 'Rank IC': 0.013, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-03-17', '2025-09-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.127', 'weight': '0.026'}

	Recorder: 5f6452a053214304b1320cf3848deff4

		Model: {'id': '5f6452a053214304b1320cf3848deff4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.21, 'Rank IC': 0.037, 'Rank ICIR': 0.373}, 'data_train_vec': ['2025-03-17', '2025-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.373', 'weight': '0.077'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260317_11 956670430626268989 (Recorders: 3/5)

	Recorder: ccc11caea84c43878240352a122800d2

		Model: {'id': 'ccc11caea84c43878240352a122800d2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.055, 'Rank IC': 0.025, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-03-17', '2024-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.137', 'weight': '0.028'}

	Recorder: 6bd1cb171baf448b86fbc7a263362d8d

		Model: {'id': '6bd1cb171baf448b86fbc7a263362d8d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.169, 'Rank IC': 0.026, 'Rank ICIR': 0.209}, 'data_train_vec': ['2024-03-17', '2025-09-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.209', 'weight': '0.043'}

	Recorder: 205b11f82c1c46f19426ada666db1f32

		Model: {'id': '205b11f82c1c46f19426ada666db1f32', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.176, 'Rank IC': 0.07, 'Rank ICIR': 0.492}, 'data_train_vec': ['2025-03-17', '2025-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17'], 'rank_icir': '0.492', 'weight': '0.102'}
