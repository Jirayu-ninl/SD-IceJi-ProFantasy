# ProFantasy

#### " ProFantasy was tested with a huge of scenarios, and fine-tuning several times to ensure that you will be able to create a FANTASY image in your own way "
This model merges with my own 3 models called R-base (realistic), F-base (Fantasy), and V-base (Vibrant) mixed together with 3 formulas Real, Mix, and Max (but in v2, these will combine into one)

** *** This Model needs VAE !!! *** **

#### Overview:

* The purpose of this model is to generate epic fantasy images not only Realistic but Animation also.
* These models require a VAE. You can try mse-840000-ema or anything. I have a photo of the comparison in the Comparision section (below)
* If you got bugs, adding '--no-half-vae' to the argument will solve it.

#### Recommends:

* You use it with any steps, prompt, sampler, ... (anything you want)
* Prompt: If you don't know what to prompt, Fantasy Prompts by TxcTrtl is a great choice.
* * Steps: I recommend 30-40, 60-80, and 120-150 (around 100, I think it's not well)
* Sampler: I developed it with DPM++ 2S a Karras, so I recommend this sampler (but others also work fine)
* Sizes: 512x512, 512x768, 512x904 (Can be used both vertically and horizontally). Not recommended sizes more than 768x768
* Hires. fix: Use Denoising strength less than 0.6 (but you can try >= 0.7, sometimes you will get problems with the hands)
* Lora: It works perfectly with VFX Lora by @DitamAi, and EPI Noise Offset.
* I do not recommend using Face Lora because you will lose a fantasy style but you can try if you know what you want from it

#### Versioning:

* v1: pilot version
  * v1-Real: Cinematic style, Realistic photo, less fantasy (if you have a fast GPU and you will generate a batch of many images, I suggest this version)
  * v1-Max: Ultra Fantasy, Concept Art, Animation, Semi-realistic (If you want semi-realistic or you plan to use img2img to make the image look more realistic, I suggest this version)
  * v1-Mix: Mix both versions (This is for lazy people who want something in the middle)
* v2: All of the above, can generate everything (depending on your prompt)

#### Download

https://civitai.com/models/52298/

#### Disclaimers:

* Do not sell: on any website.
* Credit: If you use my model in your own merges
* Not authorized: to be used on generative services (without my permission)
