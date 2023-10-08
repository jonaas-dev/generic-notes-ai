<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Generic](#generic)
  - [AI Generator](#ai-generator)
  - [Workspaces](#workspaces)
- [:open_file_folder: Audio](#open_file_folder-audio)
    - [Audio to Doc](#audio-to-doc)
- [:open_file_folder: Video](#open_file_folder-video)
    - [Video editing](#video-editing)
    - [Video assistant](#video-assistant)
- [:open_file_folder: Text](#open_file_folder-text)
    - [Text To Video](#text-to-video)
    - [Text To Room](#text-to-room)
    - [:warning: Text to Image](#warning-text-to-image)
      - [DALL-E](#dall-e)
      - [Firefly](#firefly)
      - [Parti](#parti)
      - [Stable_diffusion](#stable_diffusion)
      - [Other text-to-image generation](#other-text-to-image-generation)
    - [Text to Audio](#text-to-audio)
- [:open_file_folder: Image](#open_file_folder-image)
    - [Image Editing](#image-editing)
- [:open_file_folder: Coding](#open_file_folder-coding)
    - [Codex](#codex)
    - [Copilot](#copilot)
- [:open_file_folder: Speech recognition](#open_file_folder-speech-recognition)
    - [Whisper](#whisper)
- [:open_file_folder: Chat-Bot](#open_file_folder-chat-bot)
    - [Alpaca](#alpaca)
    - [ChatGPT](#chatgpt)
    - [Dolly](#dolly)
    - [Koala](#koala)
    - [Llama](#llama)
    - [Vicuna](#vicuna)
- [:open_file_folder: Prompting ...](#open_file_folder-prompting-)
  - [Fonts](#fonts)
  - [Guides](#guides)
  - [Security](#security)
  - [:memo: Articles](#memo-articles)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Generic

## AI Generator

- <https://gamma.app/>
- <https://www.jasper.ai/>
- <https://www.copy.ai/>
- <https://runwayml.com/>

## Workspaces

- [Window: use your own AI models on the web](https://github.com/alexanderatallah/window.ai)

# :open_file_folder: Audio
<!-- //////////////////////////////////////////////////////////////////// -->

### Audio to Doc

:rocket: Services

- <https://audio2doc.app/>

# :open_file_folder: Video
<!-- //////////////////////////////////////////////////////////////////// -->

### Video editing

:rocket: Services

- <https://kuai-lab.github.io/soundini-gallery>
- <https://duyguceylan.github.io/pix2video.github.io>
- <https://github.com/mayuelala/FollowYourPose>

### Video assistant

:rocket: Services

- <https://github.com/haotian-liu/LLaVA>

# :open_file_folder: Text
<!-- //////////////////////////////////////////////////////////////////// -->

### Text To Video

:rocket: Services

- <https://github.com/Picsart-AI-Research/Text2Video-Zero>

### Text To Room

:rocket: Services

- <https://lukashoel.github.io/text-to-room>

### :warning: Text to Image

#### DALL-E

[Go to ...](../LLMs/dall-e.md)

#### Firefly

- <https://firefly.adobe.com/>

#### Parti

- <https://parti.research.google/>

#### Stable_diffusion

[Go to ...](../LLMs/stable-diffusion.md)

#### Other text-to-image generation

- <https://laion.ai/blog/paella>

### Text to Audio

:rocket: Services

- <https://github.com/suno-ai/bark>

# :open_file_folder: Image
<!-- //////////////////////////////////////////////////////////////////// -->
### Image Editing

:rocket: Links

- [Inpaint-Anything](https://github.com/geekyutao/Inpaint-Anything)
- <https://ziqihuangg.github.io/projects/reversion.html>
- [magic-copy](<https://github.com/kevmo314/magic-copy>)
- [GFPGAN](<https://github.com/TencentARC/GFPGAN>) is a `face restorer`. It helps repairing the weird faces that Stable Diffusion generates sometimes. You first create an image using Stable Diffusion and then use GFPGAN to make the face look better.

# :open_file_folder: Coding
<!-- //////////////////////////////////////////////////////////////////// -->

### Codex

OpenAI Codex is an AI model that parses natural language and generates code. It powers GitHub Copilot, an auto completion tool, and is based on GPT-3. It has been trained on 159 GB of Python code from 54M GitHub repos.

### Copilot

# :open_file_folder: Speech recognition

### Whisper

Whisper is a powerful speech recognition and translation model trained on 680,000 hours of multilingual data. It uses an encoder-decoder architecture to convert audio into text and it also supports language identification, phrase-level timestamps, and multilingual transcription.

# :open_file_folder: Chat-Bot
<!-- //////////////////////////////////////////////////////////////////// -->

### Alpaca

### ChatGPT

[Go to ...](../LLMs/chatgpt.md)

### Dolly

### Koala

### Llama

### Vicuna

# :open_file_folder: Prompting ...

## Fonts

- <https://stablediffusionweb.com/prompts>
- <https://prompthero.com/>
- <https://www.promptstacks.com/>
- <https://www.ordinarypeopleprompts.com/>
- <https://promptperfect.jina.ai/>

## Guides

- <https://github.com/dair-ai/Prompt-Engineering-Guide>
- <https://learnprompting.org/docs/intro>

## Security

- `prompt-injection` ([click](https://simonwillison.net/series/prompt-injection/)).
- `Jailbreak [ChatGPT DAN - Jailbreak`
  - (DAN 5) <https://knowyourmeme.com/memes/events/chatgpt-dan-50-jailbreak>
  - (DAN 6) <https://www.reddit.com/r/ChatGPT/comments/10vinun/presenting_dan_60/?ref=matt-rickard.com>

## :memo: Articles

- :green_circle: [In defense of prompt engineering](https://simonwillison.net/2023/Feb/21/in-defense-of-prompt-engineering/)
    1. You need really great communication skills.
    2. the scientific method
    3. run experiments
    4. Being able to resist superstitious thinking is really important
- :green_circle: [Talking to AI Might Be the Most Important Skill of This Century](https://archive.ph/xm3Ck#selection-535.0-535.63)
- [Prompting Is Programming: A Query Language For Large Language Models](https://arxiv.org/abs/2212.06094?ref=matt-rickard.com)
- :orange_circle: [Prompt Engineering Shouldn't Exist](https://matt-rickard.com/prompt-engineering-shouldnt-exist?ref=matt-rickard.com)
  - Today, the state of the art is prompt concatenation or prompt templating.
  - Good prompts specify structured data as inputs and outputs.
  - prompt is templated
  - What if one prompt isn't enough?
  - ...
- [Controllable text generation](https://lilianweng.github.io/posts/2021-01-02-controllable-text-generation/)
- [Prompt Engineerting](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/#tips-for-example-ordering)