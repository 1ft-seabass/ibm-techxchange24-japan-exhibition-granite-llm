# Try Ollama + Code Engine + Granite

![alt text](images/00-simple-try-ja/00-simple-try-ja.png)

Ollama can ease to use IBM published open sourse LLM named IBM Granite.

![alt text](images/00-simple-try-ja/00-simple-try-ja-1.png)

Ollama'blog article also inform IBM Granite 3.0 model collaboration in https://ollama.com/blog/ibm-granite .

## Let's launch GitHub CodeSpaces

This article explain in my 2024/11/08 knowledge.

Please launch GitHub CodeSpaces on a latest Google Chrome browser.

![alt text](images/00-simple-try-ja/00-simple-try-ja-2.png)

First, login as your GitHub account. Then, click "Blank" template https://github.com/codespaces/templates .

This operation will open a CodeSpace at new browser tab.

Please wait launching GitHub CodeSpaces for a moment.

![alt text](images/00-simple-try-ja/00-simple-try-ja-3.png)

Launched!

## Let's install Ollama

The https://github.com/ollama/ollama article has the way of installing  Ollama.

![alt text](images/00-simple-try-ja/00-simple-try-ja-5.png)

The picture's a red border rect indicate Terminal for entering commands.

```
curl -fsSL https://ollama.com/install.sh | sh
```

Please type the above command and press Enter to run it.

![alt text](images/00-simple-try-ja/00-simple-try-ja-4.png)

If you copy and paste the command first, you get a clipboard confirming dialog. Please accept like this in the browser address area.

![alt text](images/00-simple-try-ja/00-simple-try-ja-6.png)

It progress installing...

![alt text](images/00-simple-try-ja/00-simple-try-ja-7.png)

It finished install.

## Let's launch Ollama

```
ollama serve
```

Please type the above command and press Enter to run it.

![alt text](images/00-simple-try-ja/00-simple-try-ja-8.png)

It launched Ollama server.

## Let's launch a new Terminal.

![alt text](images/00-simple-try-ja/00-simple-try-ja-9.png)

The terminal where the Ollama server was running at the time remains the same.

Please click the + button in the top right corner to start a new terminal.

![alt text](images/00-simple-try-ja/00-simple-try-ja-10.png)

It launched a new terminal.

![alt text](images/00-simple-try-ja/00-simple-try-ja-11.png)

These terminals can be switched using the UI on the right. Let's continue this time.

## Let's install MoE LLM model.

https://ollama.com/blog/ibm-granite has a lotp of curious LLMs. This time, let's try the Mixture of Expert (MoE) models for low latency.

```
ollama run granite3-moe
```

Please type the above command in the current new terminal and press Enter to run it.

![alt text](images/00-simple-try-ja/00-simple-try-ja-12.png)

It start downloading.

![alt text](images/00-simple-try-ja/00-simple-try-ja-13.png)

It continue downloading.

![alt text](images/00-simple-try-ja/00-simple-try-ja-14.png)

It prepared various preparations. It will say success. You will be able to sending a message!

## Let's try

![alt text](images/00-simple-try-ja/00-simple-try-ja-15.png)

Please type a message in this area.

![alt text](images/00-simple-try-ja/00-simple-try-ja-16.png)

Let's type "Do you know IBM?" and press Enter.

![alt text](images/00-simple-try-ja/00-simple-try-ja-17.png)

> , IBM is a multinational technology company headquartered in Armonk, New York. It was founded in 1911 
and is known for its computing hardware, middleware, software, consulting, and services, as well as for its 
activities in various areas including AI, quantum computing, and blockchain. IBM has been a global leader 
in the technology industry for over a century.

It will response like this message!

This trying has grate experience such fast downloading LLM data and fairly  fast responsing!