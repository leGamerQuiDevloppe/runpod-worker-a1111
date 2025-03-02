# Get Options

## Request

```json
{
  "input": {
    "api": {
      "method": "GET",
      "endpoint": "/sdapi/v1/options"
    },
    "payload": {}
  }
}
```

## Response

### RUN

```json
{
  "id": "83bbc301-5dcd-4236-9293-a65cdd681858",
  "status": "IN_QUEUE"
}
```

### RUNSYNC

```json
{
  "delayTime": 1159,
  "executionTime": 346,
  "id": "sync-d2350812-0362-4484-894e-5c173375bd1f",
  "output": {
    "CLIP_stop_at_last_layers": 1,
    "ESRGAN_tile": 192,
    "ESRGAN_tile_overlap": 8,
    "add_model_hash_to_info": true,
    "add_model_name_to_info": true,
    "add_user_name_to_info": false,
    "add_version_to_infotext": true,
    "always_discard_next_to_last_sigma": false,
    "auto_vae_precision": true,
    "clean_temp_dir_at_start": false,
    "code_former_weight": 0.5,
    "comma_padding_backtrack": 20,
    "cross_attention_optimization": "Automatic",
    "dataset_filename_join_string": " ",
    "dataset_filename_word_regex": "",
    "ddim_discretize": "uniform",
    "deepbooru_escape": true,
    "deepbooru_filter_tags": "",
    "deepbooru_sort_alpha": true,
    "deepbooru_use_spaces": true,
    "dimensions_and_batch_together": true,
    "directories_filename_pattern": "[date]",
    "directories_max_prompt_words": 8,
    "disable_all_extensions": "none",
    "disable_mmap_load_safetensors": false,
    "disable_token_counters": false,
    "disable_weights_auto_swap": true,
    "disabled_extensions": [],
    "do_not_show_images": false,
    "dont_fix_second_order_samplers_schedule": false,
    "enable_batch_seeds": true,
    "enable_emphasis": true,
    "enable_pnginfo": true,
    "enable_quantization": false,
    "eta_ancestral": 1,
    "eta_ddim": 0,
    "eta_noise_seed_delta": 0,
    "experimental_persistent_cond_cache": false,
    "export_for_4chan": true,
    "extra_networks_add_text_separator": " ",
    "extra_networks_card_height": 0,
    "extra_networks_card_show_desc": true,
    "extra_networks_card_text_scale": 1,
    "extra_networks_card_width": 0,
    "extra_networks_default_multiplier": 1,
    "extra_networks_hidden_models": "When searched",
    "extra_networks_show_hidden_directories": true,
    "face_restoration_model": "CodeFormer",
    "face_restoration_unload": false,
    "font": "",
    "gradio_theme": "Default",
    "grid_background_color": "#ffffff",
    "grid_extended_filename": false,
    "grid_format": "png",
    "grid_only_if_multiple": true,
    "grid_prevent_empty_spots": false,
    "grid_save": true,
    "grid_save_to_dirs": true,
    "grid_text_active_color": "#000000",
    "grid_text_inactive_color": "#999999",
    "grid_zip_filename_pattern": "",
    "hidden_tabs": [],
    "hide_samplers": [],
    "hires_fix_show_prompts": false,
    "hires_fix_show_sampler": false,
    "hires_fix_use_firstpass_conds": false,
    "img2img_background_color": "#ffffff",
    "img2img_color_correction": false,
    "img2img_editor_height": 720,
    "img2img_fix_steps": false,
    "img_downscale_threshold": 4,
    "img_max_size_mp": 200,
    "infotext_styles": "Apply if any",
    "initial_noise_multiplier": 1,
    "inpainting_mask_weight": 1,
    "interrogate_clip_dict_limit": 1500,
    "interrogate_clip_max_length": 48,
    "interrogate_clip_min_length": 24,
    "interrogate_clip_num_beams": 1,
    "interrogate_clip_skip_categories": [],
    "interrogate_deepbooru_score_threshold": 0.5,
    "interrogate_keep_models_in_memory": false,
    "interrogate_return_ranks": false,
    "jpeg_quality": 80,
    "js_modal_lightbox": true,
    "js_modal_lightbox_gamepad": false,
    "js_modal_lightbox_gamepad_repeat": 250,
    "js_modal_lightbox_initially_zoomed": true,
    "k_sched_type": "Automatic",
    "keyedit_delimiters": ".,\\/!?%^*;:{}=`~()",
    "keyedit_move": true,
    "keyedit_precision_attention": 0.1,
    "keyedit_precision_extra": 0.05,
    "list_hidden_files": true,
    "live_preview_content": "Prompt",
    "live_preview_refresh_period": 1000,
    "live_previews_enable": true,
    "live_previews_image_format": "png",
    "localization": "None",
    "memmon_poll_rate": 8,
    "multiple_tqdm": true,
    "n_rows": -1,
    "no_dpmpp_sde_batch_determinism": false,
    "outdir_extras_samples": "outputs/extras-images",
    "outdir_grids": "",
    "outdir_img2img_grids": "outputs/img2img-grids",
    "outdir_img2img_samples": "outputs/img2img-images",
    "outdir_init_images": "outputs/init-images",
    "outdir_samples": "",
    "outdir_save": "log/images",
    "outdir_txt2img_grids": "outputs/txt2img-grids",
    "outdir_txt2img_samples": "outputs/txt2img-images",
    "pad_cond_uncond": false,
    "pin_memory": true,
    "postprocessing_enable_in_main_ui": [],
    "postprocessing_operation_order": [],
    "print_hypernet_extra": false,
    "quicksettings_list": [
      "sd_model_checkpoint",
      "sd_vae",
      "CLIP_stop_at_last_layers"
    ],
    "randn_source": "GPU",
    "realesrgan_enabled_models": [
      "R-ESRGAN 4x+",
      "R-ESRGAN 4x+ Anime6B"
    ],
    "restore_config_state_file": "",
    "return_grid": true,
    "return_mask": false,
    "return_mask_composite": false,
    "rho": 0,
    "s_churn": 0,
    "s_min_uncond": 0,
    "s_noise": 1,
    "s_tmin": 0,
    "samplers_in_dropdown": true,
    "samples_filename_pattern": "",
    "samples_format": "png",
    "samples_log_stdout": false,
    "samples_save": true,
    "save_images_add_number": true,
    "save_images_before_color_correction": false,
    "save_images_before_face_restoration": false,
    "save_images_before_highres_fix": false,
    "save_init_img": false,
    "save_mask": false,
    "save_mask_composite": false,
    "save_optimizer_state": false,
    "save_selected_only": true,
    "save_to_dirs": true,
    "save_training_settings_to_txt": true,
    "save_txt": false,
    "sd_checkpoint_cache": 0,
    "sd_checkpoint_hash": null,
    "sd_hypernetwork": "None",
    "sd_model_checkpoint": "deliberate_v2.safetensors",
    "sd_unet": "Automatic",
    "sd_vae": "vae-ft-mse-840000-ema-pruned.safetensors",
    "sd_vae_as_default": true,
    "sd_vae_checkpoint_cache": 0,
    "sdxl_crop_left": 0,
    "sdxl_crop_top": 0,
    "sdxl_refiner_high_aesthetic_score": 6,
    "sdxl_refiner_low_aesthetic_score": 2.5,
    "send_seed": true,
    "send_size": true,
    "show_progress_every_n_steps": 10,
    "show_progress_grid": true,
    "show_progress_in_title": true,
    "show_progress_type": "Approx NN",
    "show_progressbar": true,
    "show_warnings": false,
    "sigma_max": 0,
    "sigma_min": 0,
    "target_side_length": 4000,
    "temp_dir": "",
    "textual_inversion_add_hashes_to_infotext": true,
    "textual_inversion_print_at_load": false,
    "token_merging_ratio": 0,
    "token_merging_ratio_hr": 0,
    "token_merging_ratio_img2img": 0,
    "training_enable_tensorboard": false,
    "training_image_repeats_per_epoch": 1,
    "training_tensorboard_flush_every": 120,
    "training_tensorboard_save_images": false,
    "training_write_csv_every": 500,
    "training_xattention_optimizations": false,
    "ui_extra_networks_tab_reorder": "",
    "ui_reorder_list": [
      "inpaint",
      "sampler",
      "checkboxes",
      "hires_fix",
      "dimensions",
      "cfg",
      "seed",
      "batch",
      "override_settings",
      "scripts"
    ],
    "ui_tab_order": [],
    "uni_pc_lower_order_final": true,
    "uni_pc_order": 3,
    "uni_pc_skip_type": "time_uniform",
    "uni_pc_variant": "bh1",
    "unload_models_when_training": true,
    "upcast_attn": false,
    "upscaler_for_img2img": null,
    "upscaling_max_images_in_cache": 5,
    "use_old_emphasis_implementation": false,
    "use_old_hires_fix_width_height": false,
    "use_old_karras_scheduler_sigmas": false,
    "use_original_name_batch": true,
    "use_save_to_dirs_for_ui": false,
    "use_upscaler_name_as_suffix": false,
    "webp_lossless": false
  },
  "status": "COMPLETED"
}
```