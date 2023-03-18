# YTGPT
YTGPT is a Google Chrome extension that uses the power of OpenAI's GPT-3 language model to provide users with summaries of YouTube videos. With YTGPT installed in your Chrome browser, you can easily get a summary of a video without having to watch the entire thing.

YTGPT's summarization feature is particularly useful for those who don't have the time to watch lengthy YouTube videos, but still want to know the key points and takeaways. By simply clicking the YTGPT icon while watching a video, you can quickly generate a summary that captures the essence of the video.

https://user-images.githubusercontent.com/54985621/226095065-93854bb9-3e81-4249-b918-8286e51dce1d.mp4

# Usage
Unpack and install the chrome extension.

Run the `summarize.py` script which will spin up a simple http server to summarize videos provided by the chrome extension.

The required dependencies can be installed by running the following command:

```sh
pip install tiktoken backoff openai youtube-transcript-api bottle Paste
```
