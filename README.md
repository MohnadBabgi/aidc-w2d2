# aidc-w2d2
Lab W2D2: wrap the model

![Server startup](images/Screenshot%202026-08-24%20143249.jpg)
*The Uvicorn server loading the Qwen2.5-0.5B-Instruct model and handling incoming API requests (health checks, model listing, and chat completions).*

![API test with curl](images/Screenshot%202026-08-24%20144141.jpg)
*Testing the OpenAI-compatible `/v1/chat/completions` endpoint via `curl`, showing a successful streaming response from the locally hosted Qwen model.*