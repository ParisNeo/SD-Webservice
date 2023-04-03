# SD-Webservice :Remote Image Generator Extension for Stable Diffusion WebUI
A stable diffusion webservice to enable applications to trigger the generation of Stable diffusion art.

This application is an extension to the Stable Diffusion WebUI application available at https://github.com/AUTOMATIC1111/stable-diffusion-webui. It adds the functionality to create a web service that can be triggered for external applications to perform image generation from text prompts.

## Installation

To install this application, follow these steps:

1. Download or clone this repository.
2. Copy the downloaded/clone files to the `extensions` directory of the Stable Diffusion WebUI application.
3. Enable the extension by checking the enable checkbox in the main interface of the Stable Diffusion WebUI application.

The service will be available at port 9601 after installation.

## Usage

To call the service, you can do a GET or POST request to `/imagine?prompt=<the prompt>&dest_path=<path to destination>`. The `prompt` parameter should contain the text prompt for the image you want to generate, and the `dest_path` parameter should contain the path to the destination directory where the generated image will be saved.

## License

This application is licensed under the MIT license. See the `LICENSE` file for more information.

## Contribution

If you find any bugs or have ideas for new features, feel free to create an issue or submit a pull request on GitHub. We welcome contributions from the community!
