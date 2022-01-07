# DeepRiverFCNNs


### Requirements
model index 

### Examples

Model Training:
```python
python train_fcnn.py --checkpoint_dir ckpts --data_path TensorFlowRecords --figure_path figs --data_dim 1 --model_index 1 --num_epoch 2 --batch_size 24 --learning_rate 0.1
```

Inference:
```python
python inference_fcnn.py --checkpoint_path checkpoints/Panchromatic/U-Net/ResNet18/cp.080.ckpt --input_path test_tiffimg_pan.tif --output_folder . --data_dim 1 --model_index 2 --downscale_factor 6 --mask_name mask_pan.tif
```

### Reference

