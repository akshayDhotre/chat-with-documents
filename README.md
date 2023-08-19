# chat-with-documents
## Chat with your documents using chatdocs library

### This is a project based on amazing library "marella/chatdocs" available on Github
### Link - https://github.com/marella/chatdocs


**Following instructions are taken from README file of original repository for easy setup,please follow original README for details.**

## Installation
</details>

Install the tool using:

```sh
pip install chatdocs
```

Download the AI models using:

```sh
chatdocs download
```

Now it can be run offline without internet connection.

## Usage

Add a directory containing documents to chat with using:

```sh
chatdocs add /path/to/documents
```

> The processed documents will be stored in `db` directory by default.

Chat with your documents using:

```sh
chatdocs ui
```

Open http://localhost:5000 in your browser to access the web UI.

It also has a nice command-line interface:

```sh
chatdocs chat
```

## Configuration
* All the configuration options can be changed using the `chatdocs.yml` config file. 
* Create a `chatdocs.yml` file in some directory and run all commands from that directory. 

* For reference, see the default [`chatdocs.yml`](https://github.com/marella/chatdocs/blob/main/chatdocs/data/chatdocs.yml) file.

## Configuration updates in this reposiroty
* I have changed **ctransformers** and **huggingface** models to use new GGML model created form LlaMA 2 model.

* Changes in configuration can be seen in *chatdocs.yml* file 

* Model Link - https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML