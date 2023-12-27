# KATI-LLAMA (local large language model chat)
[![GitHub](https://img.shields.io/github/license/hswlab/kati-llama)](https://github.com/hswlab/kati-llama/blob/main/LICENSE) 
![GitHub issues](https://img.shields.io/github/issues/hswlab/kati-llama)
[![Downloads](https://img.shields.io/github/v/release/hswlab/kati-llama)](https://github.com/hswlab/kati-llama/releases/latest) 

KATI-LLAMA is an interface for chatting with Large Language Models on a private PC. The Language Model can 
be downloaded automatically in the settings and then used offline.
The KATI application allows the user to communicate with an AI in a human-like manner. The AI's responses 
can be output with a natural voice and the AI's avatar image changes appearance depending on the chatbot's 
mood. Below is a summary of the features of KATI-LLAMA.


[![GitHub release (with filter)](https://img.shields.io/github/downloads/hswlab/kati-llama/total?style=for-the-badge&logo=ChatBot&label=download%20KATI-LLAMA
)](https://github.com/hswlab/kati-llama/releases/latest)


*Key features of KATI:*
- [X] Talk to AI without an internet connection
- [X] Optional voice output with a voice pre-installed in the operating system or a natural-sounding TikTok voice. (The TikTok voice requires an internet connection)
- [X] Voice input (System Speech or Whisper)
- [X] Dynamic avatar images to represent AI emotions.
- [X] Chat history with filter function and read-aloud function.
- [X] Rating function for AI responses as an aid to the filter function
- [X] Reduce wait times by streaming responses directly. (If the read-aloud function is active, the output only happens when the sentence is complete)
- [X] Text and code are formatted for better readability.
- [X] Multilingual user interface (DE, EN, FR, ES, PT, JA, KO)

![preview](https://github.com/hswlab/kati-llama/blob/main/Screenshot.png)

![preview2](https://github.com/hswlab/kati-llama/blob/main/Screenshot2.png)

![preview3](https://github.com/hswlab/kati-llama/blob/main/Screenshot3.png)

# Demonstration of how to install and use KATI-LLAMA (German)
[![KATI-LLAMA](https://i9.ytimg.com/vi/rMKaL4mhw5A/mq2.jpg?sqp=CMT1sKwG-oaymwEmCMACELQB8quKqQMa8AEB-AHUBoAC4AOKAgwIABABGD4gTShyMA8=&rs=AOn4CLBonb_d-FqGfQk-LnXJJk7A4HSR6w)](https://youtu.be/rMKaL4mhw5A)

# Demonstration of how to use STT in KATI-LLAMA (German)
[![STT in KATI-LLAMA](https://i9.ytimg.com/vi_webp/N8AAO0Dv5gc/mq2.webp?sqp=CMDusKwG-oaymwEmCMACELQB8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGGUgZShlMA8=&rs=AOn4CLBuqrBwb_HC_vhL0HQY7MDcR5s23A)](https://youtu.be/N8AAO0Dv5gc?si=fwluaWGYE48Juv7D)


# Nuget packages and associated licenses used in KATI
- LLamaSharp <a href="https://licenses.nuget.org/MIT">`MIT License`</a>
- ElectronNET.API <a href="https://licenses.nuget.org/MIT">`MIT License`</a>
- Esprima <a href="https://licenses.nuget.org/BSD-3-Clause">`BSD 3-Clause License`</a>
- LiteDB <a href="https://www.nuget.org/packages/LiteDB/5.0.16/license">`MIT License`</a>
- Microsoft.AspNetCore.SignalR.Client <a href="https://licenses.nuget.org/MIT">`MIT License`</a>
- NAudio <a href="https://www.nuget.org/packages/NAudio/2.2.1/license">`License Info`</a>
- Newtonsoft.Json <a href="https://licenses.nuget.org/MIT">`MIT License`</a>
- System.Data.SQLite <a href="https://www.sqlite.org/copyright.html">`Public Domain`</a>
- System.Linq.Async <a href="https://licenses.nuget.org/MIT">`MIT License`</a>
- System.Speech  <a href="https://licenses.nuget.org/MIT">`MIT License`</a>
- SoundTouch <a href="https://www.surina.net/soundtouch/license.html">`License Info`</a>
- WhisperNet <a href="https://licenses.nuget.org/MPL-2.0">`MPL-2.0 License`</a>


# Next milestone (research)
- [ ] Add more Language Models in the settings for download.

# Known bugs that will be fixed soon
- [ ] Can't find any bugs yet :)

# Performance issues
- Depending on the model configured, more or 
less RAM and processor power are required. 
This can affect the performance of the AI's responses. Try a smaller model and see if the AI 
responds faster. Keep in mind that the smaller 
the model, the lower the quality of the responses.
- Slow output may also be due to the configured 
processor setting. AVX is very slow, but it is 
mostly supported by older processors. With 
AVX2, the latency is significantly lower, but not 
all processors support it. Try chatting with 
AVX2 to see if it works for you.
- If the read-aloud function is enabled, the program waits to output until a complete sentence is available. To minimize the response 
time, you can disable the audio output, then 
the response text will be streamed without interruption. 
- The AI sometimes takes longer to answer in 
general if it finds little information about a 
question. In this case, you can try to cancel the 
chat session and rephrase the question

