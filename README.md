# Usage

## Train

```
python train.py --config-file=config_r3d.yaml
```

## Adversarial Attack

```
python adversarial_attack.py --config-file=config_r3d.yaml
```

* List of Attack Methods : gluoncv.torch.utils.torchattack
* Applying Attack Methods : gluoncv.torch.utils.adversarial_classification

## Config.yaml

* You need to change IP address in DIST_URL and WOLRD_URLS to your local or server IP.