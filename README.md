# Sound Event Detection and Clustering for Bioacoustic Vocalizations

This repository contains the code and documentation for **"Sound Event Detection and Clustering for Bioacoustic Vocalizations,"** a final year project at the University of Stellenbosch, completed as part of the Bachelor of Engineering (BEng) degree in Electrical and Electronic Engineering, Informatics stream.

## Project Overview

### Purpose
The primary goal of this project is to develop an unsupervised system for detecting and clustering sound events within bioacoustic recordings. This system focuses on analyzing and classifying vocalizations produced by marine life, such as fish and whales, while filtering out anthropogenic noises like boat engines. By leveraging advanced feature extraction, clustering algorithms, and endpoint detection, this project aims to contribute to the study of marine biodiversity and the impacts of human activities on aquatic ecosystems.

### Key Features
- **Sound Event Detection:** Automatically identifies distinct sound events within continuous bioacoustic recordings.
- **Unsupervised Clustering:** Groups detected sound events into clusters based on their acoustic characteristics without requiring labeled data.
- **Endpoint Detection:** Precisely determines the start and end points of sound events within audio streams.
- **Bioacoustic Focus:** Specifically designed for the analysis of bioacoustic vocalizations in marine environments.

## Project Structure

The repository is organized as follows:

```
/SoundEventClustering
├── code/        # Source code for feature extraction, clustering, and evaluation
├── data/        # Local directory for storing audio recordings (excluded from version control)
├── notebooks/   # Jupyter notebooks for experimentation and analysis
└── README.md    # Project documentation
```

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/josephthehansen-stellenbosch/skripsie.git
    cd skripsie
    ```

2. **Install dependencies:**

    Ensure that you have Python 3.8+ installed. Install the required packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up the environment:**

    If required, create a `.env` file to configure environment variables such as paths to data files.

## Usage

### Data Preparation

Place your hydrophone audio recordings in the `data/` directory. This directory is excluded from version control to manage large files efficiently.

### Running the System

You can start the sound event detection and clustering process by executing the main script:

```bash
python code/main.py
```

For more detailed instructions, refer to the Jupyter notebooks in the `notebooks/` directory.

## Acknowledgements

This project was developed as a final year skripsie project in the Informatics stream of the BEng in Electrical and Electronic Engineering at the University of Stellenbosch. Special thanks to:

- **[Prof. Jaco Versfeld](https://scholar.google.co.za/citations?user=k7cFxuQAAAAJ&hl=en):** For invaluable guidance and support throughout the project.
- **University of Stellenbosch:** For providing the resources and academic environment that made this project possible.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact Information

For any inquiries or further information, please contact:

- **Joseph Hansen**
- **Email:** [Email](mailto:26100428@sun.ac.za)
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/joseph-h-926060128/)

## Future Work

Potential future enhancements to the project could include:

- Integration with real-time audio processing pipelines.
- Expansion of the system to include other types of bioacoustic signals.
- Application of deep learning methods for improved clustering accuracy.

## Conclusion

This project represents a significant step towards the automatic classification and analysis of bioacoustic vocalizations, contributing to the broader field of marine ecology and bioacoustics. The system developed herein is a versatile tool that can be adapted and expanded for various research and monitoring applications.
