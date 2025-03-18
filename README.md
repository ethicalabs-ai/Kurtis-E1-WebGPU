---
title: SmolLM WebGPU
emoji: 🤏
colorFrom: blue
colorTo: indigo
sdk: static
pinned: false
license: apache-2.0
models:
  - ethicalabs/Kurtis-SmolLM2-135M-Instruct-DPO-ONNX
short_description: An empathetic assistant that runs locally in your browser
---

# SmolLM WebGPU

A simple React + Vite application for running [Kurtis-SmolLM2-135M-Instruct](https://huggingface.co/ethicalabs/Kurtis-SmolLM2-135M-Instruct-DPO-ONNX), a powerful small language model, locally in the browser using Transformers.js and WebGPU-acceleration.

## Getting Started

Follow the steps below to set up and run the application.

### 1. Clone the Repository

Clone the examples repository from GitHub:

```sh
git clone https://github.com/huggingface/transformers.js-examples.git
```

### 2. Install Dependencies

Install the necessary dependencies using npm:

```sh
npm i
```

### 3. Run the Development Server

Start the development server:

```sh
npm run dev
```

The application should now be running locally. Open your browser and go to `http://localhost:5173` to see it in action.
