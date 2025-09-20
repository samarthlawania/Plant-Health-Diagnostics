# Prakriti - Plant Health Diagnostics

Prakriti is an innovative and powerful AI-driven application designed to enhance plant care and sustainable farming practices through cutting-edge machine learning models. By harnessing the power of AI and combining it with traditional knowledge, Prakriti aims to provide personalized solutions for healthier plants and joyful farming experiences.

-----

### Table of Contents

  * [Features](https://www.google.com/search?q=%23features)
  * [Installation](https://www.google.com/search?q=%23installation)
  * [Usage](https://www.google.com/search?q=%23usage)
  * [Configuration](https://www.google.com/search?q=%23configuration)
  * [Tech Stack](https://www.google.com/search?q=%23tech-stack)
  * [Contributing](https://www.google.com/search?q=%23contributing)
  * [License](https://www.google.com/search?q=%23license)
  * [Acknowledgements](https://www.google.com/search?q=%23acknowledgements)

-----

### Features

  * **Accurate Disease Detection**: The application uses a robust AI model trained on a vast dataset of images to ensure reliable and accurate disease detection in plant leaves.
  * **Tailored Remedies**: Beyond detection, Prakriti provides personalized remedies for identified diseases, addressing plant health issues effectively. This includes recommending specific fungicides or organic solutions and providing links to purchase them.
  * **User-Friendly Experience**: The intuitive user interface makes uploading a plant image and receiving insights a seamless process.
  * **Time and Cost Savings**: Prakriti eliminates the need for manual research and guesswork in diagnosing plant diseases, saving you time, effort, and potentially costly mistakes.
  * **Holistic Approach**: The application blends technology with the wisdom of nature to offer a holistic approach to plant care, honoring both tradition and innovation.

-----

### Installation

To run this project, you need to set up both the backend and the frontend.

#### Prerequisites

  * Node.js (for the frontend)
  * Python 3.11 (for the backend)
  * `pip`
  * `npm` or `yarn` or `pnpm` or `bun`
  * A trained PyTorch model file named `plant_disease_model_1_latest.pt` in the `backend` directory.

#### Backend Setup

1.  Navigate to the `backend` directory.
    ```bash
    cd backend
    ```
2.  Install the required Python packages.
    ```bash
    pip install -r requirements.txt
    ```
3.  Place your trained model file (`plant_disease_model_1_latest.pt`) in this directory.
4.  Start the Flask server.
    ```bash
    python app.py
    ```
    The server will run on `http://localhost:8000`.

#### Frontend Setup

1.  Navigate to the `Prakriti` directory.
    ```bash
    cd Prakriti
    ```
2.  Install the Node.js dependencies.
    ```bash
    npm install
    ```
3.  Start the Next.js development server.
    ```bash
    npm run dev
    ```
    Open `http://localhost:3000` with your browser to see the result.

-----

### Usage

Once both the backend and frontend are running, you can use the application by following these steps:

1.  Navigate to the homepage of the application.
2.  Click or tap on the image upload area to select a picture of a plant leaf. Ensure the image is clear and well-lit.
3.  The application will display the uploaded image.
4.  Click the **"Detect Disease"** button. The image will be sent to the backend for analysis.
5.  The application will display the results, including the detected disease, a description, prevention steps, and a recommended supplement with a link to purchase it.

-----

### Configuration

The backend is configured to accept image uploads up to 16MB. The frontend connects to the backend at `http://localhost:8000/submit`.

-----

### Tech Stack

**Frontend (Prakriti)**

  * Next.js
  * React
  * TypeScript
  * Tailwind CSS
  * Radix UI
  * React Query

**Backend (backend)**

  * Python 3.11
  * Flask
  * PyTorch
  * Pillow (PIL)
  * NumPy
  * Pandas
  * Flask-CORS

-----

### Contributing

Prakriti is a free and open-source project on GitHub. Your feedback helps us refine and enhance its capabilities and features. We welcome your contributions to make the project better.

-----

### License

This project is open-source. For more details, please refer to the project's GitHub page.

-----

### Acknowledgements

  * All the libraries and frameworks used in this project.
  * The project team for their dedication and shared passion for innovation.
  * Nature's wisdom for inspiring the project to create a greener and healthier world.