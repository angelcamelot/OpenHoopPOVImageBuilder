<p align="center"><a href="https://github.com/angelcamelot/OpenHoop"><img src="LOGO.png" alt="Gray shape logo" height="130"/></a></p>
<h1 align="center">POV Image Builder</h1>
<p align="center">Tool developed for OpenHoop project - Effortless POV Image Creation!</p>

<p align="center">
   <a href="https://opensource.org/"><img alt="Static Badge" src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red"></a>
   <a href="https://github.com/angelcamelot/OpenHoopPOVImageBuilder/graphs/contributors"><img alt="Contributors" src="https://img.shields.io/github/contributors/angelcamelot/OpenHoop"></a>
   <a href="https://twitter.com/intent/tweet?text=Revolutionize%20your%20LED%20hoop%20art%20with%20the%20OpenHoop%20Pixel%20Art%20Generator!%20Create%20stunning%20visuals%20effortlessly%20and%20bring%20your%20creations%20to%20life.%20Check%20it%20out:%20https://github.com/angelcamelot/OpenHoopPOVImageBuilder/&hashtags=OpenHoop,LED,PixelArt,opensource"><img src="https://img.shields.io/badge/Tweet-1DA1F2?&logo=twitter&logoColor=white" alt="Tweet" height="20"/></a>
</p><br/><br/>

## :art: Overview

The Open Hoop POV Image Builder is a Python script developed as part of the OpenHoop project. This tool enables users to generate images and corresponding code for displaying POV images on OpenHoop devices, providing an essential resource for creating captivating visuals.
## :computer: Usage

1. **Ensure Python and dependencies are installed:** Make sure you have Python 3.x installed on your system along with the necessary dependencies. You can install dependencies by running:
    ```
    pip install -r requirements.txt
    ```

2. **Run the script:** Execute the script and follow the prompts. You can run the script by navigating to its directory in the terminal and running:
    ```
    python main.py
    ```

3. **Choose import option:** When prompted, the script will automatically detect the type of image you're importing:
    - If importing a bitmap image (e.g., .bmp), the script will generate POV image instructions directly from the image.
    - If importing a normal image file (e.g., .png, .jpg, .jpeg), you'll be prompted to specify additional preferences such as grid size and color aliases.

4. **Input image path and preferences:** Enter the path to the image file and provide additional preferences such as grid size and color aliases (for normal images only). If a color is defined as "background" in the aliases, it won't be included in the list of pixels. If an alias is provided, it will be used as a variable in the POV image instructions.

5. **Generate POV image:** The script will process the input image and generate POV image instructions based on the specified preferences. The output will include both a text file containing instructions and a bitmap image of the generated POV image.

6. **Explore and use your POV image:** You can now use the generated POV image for your LED hoop art projects within the OpenHoop ecosystem.

## :gear: Requirements

- Python 3.x
- PIL (Python Imaging Library)
- prompt_toolkit

## :page_with_curl: License

This script is released under an open-source license. See the [LICENSE](LICENSE) file for details.

## :handshake: Contributing

Contributions are welcome and encouraged! If you'd like to contribute to the Pixel Art Generator or the OpenHoop project in general, please follow these steps:
- Fork the repository.
- Create your feature branch (`git checkout -b feature/your-feature-name`).
- Commit your changes (`git commit -am 'Add some feature'`).
- Push to the branch (`git push origin feature/your-feature-name`).
- Create a new Pull Request.

## :clipboard: TODOs

- Conduct thorough testing, including extensive trials with different types of images.
- Enhance user interface and error handling for a smoother experience.
- Optimize code for improved performance and readability.

## :busts_in_silhouette: Credits

This project was developed and maintained by [@angelcamelot](https://github.com/angelcamelot).

Special thanks to the following individuals and organizations for their contributions to this project:

- [Python Imaging Library (PIL)](https://pillow.readthedocs.io/en/stable/) - for providing essential image processing functionalities.
- [prompt_toolkit](https://python-prompt-toolkit.readthedocs.io/en/latest/) - for enabling user input handling in the command-line interface.
- [Python](https://www.python.org/) - for creating the programming language that powers this project.

And a big thank you in advance to all future contributors who will help improve and refine the Pixel Art Generator and the OpenHoop project.

---

_For more information about the OpenHoop project and its ecosystem, visit [here](https://github.com/angelcamelot/OpenHoop)._
