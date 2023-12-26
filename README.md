# OOD Research Pipe
I am still working on it...

## Instructions
  use `make_gen_att.sh` to generate run script
  
  use `submit.sh` to run in MSI

## Examples
  - Generate run scrip
      ```ruby
      bash make_gen_att.sh
      ```

  - Generate CIFAR10 data under FGSM attack:
      ```ruby
      python generate_attack_data.py --attack_name FGSM --dataset cifar10
      ```

  - Evaluate Mahalanobis detector under PGD attack
      ```ruby
      python detectors_eval.py --model WideResNet --attack_data PGD_cifar10 --detector Mahalanobis
      ```
  
