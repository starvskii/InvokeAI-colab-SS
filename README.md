## This is a personal modified project of camenduru/InvokeAI-colab.
Modified change log:
 - clone official InvokeAI project instead of camenduru's
 - updated to latest version v3.0.1post3 by Aug.1st
 - preinstall SDXL 1.0, openpose
 - Scan and preload the Models on your google drive!!

NOTE: 
1. pls upload your models to Googledrive: /MyDrive/InvokeAI_models/autoimport/...
2. Colab will open a window and asks to sign in to google account
![image](https://github.com/starvskii/InvokeAI-colab-SS/assets/53967896/1e13f4fd-3fb8-4257-8454-83ddcff17f4f)


WHAT I'M PLAN TO DO NEXT:
 - Add google drive as a default output path to save the jobs..
.
.
.
.
.


## Original README from camenduru are as below, follow him/her if you like it..


🐣 Please follow me for new updates https://twitter.com/camenduru

🔥 Please join our discord server https://discord.gg/k5BwmmvJJU

🥳 Please join my patreon community https://patreon.com/camenduru

## 🦒 Colab

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/InvokeAI-colab/blob/main/InvokeAI_colab.ipynb) | InvokeAI_colab v3.0

## Tutorial 
![image](https://github.com/camenduru/InvokeAI-colab/assets/54370274/25f36aa3-e4da-4bef-a951-b8b6c6aff5d3)
This is not an error or crash. We are intentionally restarting the colab. You don't need to do anything. Please execute the second cell.

![image](https://github.com/camenduru/InvokeAI-colab/assets/54370274/a2c1dd61-bef8-4bc4-bd5c-3fe0c3d88d0c)
When you see `http://127.0.0.1:9090` please click the link `http://random_text.remote.moe`

### ControlNet
ControlNet `depth` , `canny`, `openpose`, default installed. If you want more ControlNet. After running the first cell, go to `/content/InvokeAI/invokeai/configs/INITIAL_MODELS.yaml` and edit `recommended: False` to `True`.

![image](https://github.com/camenduru/InvokeAI-colab/assets/54370274/0aeecc0e-7442-478b-ab5e-b044861d5603)

### Custom models
InvokeAI has its own model installer inside the UI. Please use that tab.

## Main Repo
https://github.com/invoke-ai/InvokeAI <br />

## Docs
https://invoke-ai.github.io/InvokeAI <br />

## Output
![Screenshot 2023-07-22 191553](https://github.com/camenduru/InvokeAI-colab/assets/54370274/cbf74b6a-28e6-43f4-8882-1bf9217cafcb)
