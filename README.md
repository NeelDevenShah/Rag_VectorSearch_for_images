# Smart AI Based Image RAG

Smart AI Based Image RAG is an intelligent search system that utilizes cutting-edge technologies to provide users with efficient and intuitive image search capabilities. The system combines the power of Retrieval Augmented Generation (RAG) techniques and computer vision to enable users to discover and explore information seamlessly.

## Overview

This project aims to develop an intelligent search system with the following key features:

- Image-based search: Users can upload images to search for information based on visual content, such as objects, scenes, and patterns.
- Cloud-native architecture: The backend API is designed as a cloud-native application, allowing for easy integration into cloud-based ecosystems such as Microsoft Azure.
- Cost-effective solution: The system utilizes open-source technologies, including pre-trained models from the Hugging Face library, to optimize cost and achieve high performance and accuracy without relying on commercial APIs.

## Features

- **Image-based search**: Employs computer vision techniques to analyze uploaded images and retrieve relevant information from the database.
- **Data sources**: Utilizes the Food-101 dataset, a comprehensive collection encompassing 101 distinct food categories, for image-based search.
- **Vectorization**: Uses MongoDB for data storage and vectorization, enabling the application of Ranked Answer Grouping (RAG) for search functionality.
- **Custom API**: Implements a custom API using Flask, enabling users to interact with the RAG search system through a user-friendly interface.
- **Cloud deployment**: Deployed on Microsoft Azure, ensuring smooth operation, efficient inference processing, and proactive system management.
- **Open-source models**: Integrates pre-trained models from the Hugging Face library for image embeddings, ensuring cost-effectiveness and customization.

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/NeelDevenShah/Rag_VectorSearch_for_images.git

   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

   ```

3. Set up MongoDB Atlas for data storage and retrieval.

4. Deploy the Flask API on Microsoft Azure or any preferred cloud platform.

## Usage

1. Access the API endpoint through the provided URL.

2. Use text queries or upload images to search for restaurants, dishes, and menu items.

3. Explore search results and discover a wide range of food options available.

## Contributors

- Neel Shah - neeldevenshah.ai@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
