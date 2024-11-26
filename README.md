# Results And Observations


## Time Steps
### T-100
!CUDA_VISIBLE_DEVICES=0 python main_SDDPM.py --train --dataset='mnist' --beta_1=1e-4 --beta_T=0.02 --img_size=16 --timestep=4 --img_ch=1 --parallel=True --sample_step=0 --total_steps=5 --logdir='./logsMNIST' --wandb --eval --num_images=5000 --batch_size=64 --save_step=1000 --ch=64 --total_steps=10001 --num_workers=0  --T=100

Models Path: \SDDPM\resultsAndObservation\Timsteps\T100ckpt.pt

### T=500
!CUDA_VISIBLE_DEVICES=0 python main_SDDPM.py --train --dataset='mnist' --beta_1=1e-4 --beta_T=0.02 --img_size=16 --timestep=4 --img_ch=1 --parallel=True --sample_step=0 --total_steps=5 --logdir='./logsMNIST' --wandb --eval --num_images=5000 --batch_size=64 --save_step=1000 --ch=64 --total_steps=10001 --num_workers=0  --T=500

Models Path: \SDDPM\resultsAndObservation\Timsteps\T500ckpt.pt