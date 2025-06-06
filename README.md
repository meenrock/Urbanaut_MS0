# Quickstart

This quickstart demonstrates how to build a text summarization application with a Transformer model from the Hugging Face Model Hub.

## Prerequisites

Python 3.8+ and `pip` installed. See the [Python downloads page](https://www.python.org/downloads/) to learn more.

## Get started

Perform the following steps to run this project and deploy it to BentoCloud.

1. Clone the repository:

   ```bash
   git clone https://github.com/bentoml/quickstart.git
   cd quickstart
   ```

2. Install BentoML and the required dependencies for the model.

   ```bash
   pip install bentoml torch transformers
   ```

3. Serve your model as an HTTP server. This starts a local server at [http://localhost:3000](http://localhost:3000/), making your model accessible as a web service.
   
   ```bash
   bentoml serve
   ```

4. Once your Service is ready, you can deploy it to [BentoCloud](https://www.bentoml.com/cloud). Make sure you have [logged in to BentoCloud](https://docs.bentoml.com/en/latest/bentocloud/how-tos/manage-access-token.html) and run the following command to deploy it.

   ```
   bentoml deploy
   ```

   **Note**: Alternatively, you can manually build a Bento, [containerize it with Docker](https://docs.bentoml.com/en/latest/get-started/packaging-for-deployment.html), and deploy it in any Docker-compatible environment.

For more information, see [the Hello World example in the BentoML documentation](https://docs.bentoml.com/en/latest/get-started/hello-world.html).
