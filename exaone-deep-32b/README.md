# A EXAONE-3.5-32B node

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the EXAONE-3.5-32b model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/exaone-deep-32b-instrcut/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/LGAI-EXAONE/EXAONE-Deep-32B)
* [GGUF formatted model](https://huggingface.co/gaianet/EXAONE-Deep-32B-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
