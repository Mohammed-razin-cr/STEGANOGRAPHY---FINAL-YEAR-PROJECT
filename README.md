# Steganography Project

## Overview
This project implements steganography using Python, focusing on encoding and decoding hidden messages within image and audio files. Steganography is the practice of concealing information within other data, making it a powerful tool for secure communication.

**Note**: This is my final-year BCA project.

## Features
- **Image Steganography**: 
  - Encode text messages within image files.
  - Decode hidden text from image files.
- **Audio Steganography**: 
  - Encode text messages within audio files.
  - Decode hidden text from audio files.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - `Pillow` for image processing
  - `wave` and `numpy` for audio processing
  - `tkinter` for GUI development
  - `ctypes` for system-level operations

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Mohammed-razin-cr/STEGANOGRAPHY---FINAL-YEAR-PROJECT.git
   ```

2. Navigate to the project directory:
   ```bash
   cd steganography-project
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Image Steganography

#### Encoding
1. Place the image file in the `input` folder.
2. Run the following command:
   ```bash
   python image_steganography.py encode --image input/image.png --message "Your secret message" --output output/encoded_image.png
   ```

#### Decoding
1. Place the encoded image file in the `input` folder.
2. Run the following command:
   ```bash
   python image_steganography.py decode --image input/encoded_image.png
   ```

### Audio Steganography

#### Encoding
1. Place the audio file in the `input` folder.
2. Run the following command:
   ```bash
   python audio_steganography.py encode --audio input/audio.wav --message "Your secret message" --output output/encoded_audio.wav
   ```

#### Decoding
1. Place the encoded audio file in the `input` folder.
2. Run the following command:
   ```bash
   python audio_steganography.py decode --audio input/encoded_audio.wav
   ```

## Folder Structure
```
.
├── Decrypt-Audio         # Scripts and files for decoding hidden messages in audio
├── Decrypt-Image         # Scripts and files for decoding hidden messages in images
├── Encrypt-Audio         # Scripts and files for encoding messages into audio
├── Encrypt-Image         # Scripts and files for encoding messages into images
├── image                 # Image-related utility files
├── Logo                  # Logos and graphical assets
├── Project               # General project-related resources
├── c1.png                # Example input image 1
├── c2.png                # Example input image 2
├── ExWave.py             # Script for handling wave audio files
├── HiddenWave.py         # Script for embedding messages in wave audio
├── main.exe              # Executable for running the GUI application
├── main.py               # Main Python script for the project
├── run.py                # Script to initialize and run the application
├── STEGANOGRAPHY---FINAL-YEAR-PROJECT # Main project directory
└── README.md             # Project documentation
```

## Large File Issue
GitHub limits file uploads to 100MB. Since the project files exceed this limit, consider using alternatives like:
- [Git Large File Storage (LFS)](https://git-lfs.github.com/)
- Hosting large files on cloud storage (e.g., Google Drive, Dropbox) and sharing the link in the repository.

## Contributing
Contributions are welcome! If you'd like to improve the project or fix bugs, please follow these steps:
1. Fork this repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Python documentation
- Open-source libraries

## Contact
For any questions or suggestions, feel free to reach out:
- **Email**: [razincr32@gmail.com](mailto:razincr32@gmail.com)
- **GitHub**: [Mohammed-razin-cr](https://github.com/Mohammed-razin-cr)
- THANK YOU
