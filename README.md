<p float="left">
    <img alt="" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
    <img alt="" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
    <img alt="" src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" />
</p>

# rembgr

This extension is for AUTOMATIC1111's [Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui). Unlike other extensions for this, it is positioned directly in txt2img and img2img tabs.

### Capabilities

* Removes background after each image generation
* Can put color instead of transparent background
* Can put background image
* Can put foreground image (frame for example)

### API
Can be used with API call to **/sdapi/v1/rembgr/process** with **POST** method:
```
{
    "image": "base64 encoded image"
}
```
And the response will be:
```
{
    "image": "base64 encoded image"
}
```

### Install

Use **Install from URL** option with this repo url (full restart is required).

### Requirements
- [rembg](https://github.com/danielgatis/rembg)

All requirements will be installed on first use.

### Examples

<p float="left">
    <img width="256" src="https://github.com/ilian6806/rembgr/blob/main/static/images/00097-1988224565.png?raw=true" alt="">
    <img width="256" src="https://github.com/ilian6806/rembgr/blob/main/static/images/00098-1746741710.png?raw=true" alt="">
</p>
<br/>
<p float="left">
    <img width="256" src="https://github.com/ilian6806/rembgr/blob/main/static/images/00084-2728809108.png?raw=true" alt="">
    <img width="256" src="https://github.com/ilian6806/rembgr/blob/main/static/images/00087-2728809107.png?raw=true" alt="">
</p>

### Contributing

Feel free to submit PRs to develop!

<p align="center">
  ...and you can always buy me a :beer:! <br/><br/>
  <a href="https://www.paypal.com/paypalme/ilian6806" target="_blank">
    <img src="https://img.shields.io/badge/Donate-PayPal-green.svg" alt="Donate with PayPal"/>
  </a>
</p>

