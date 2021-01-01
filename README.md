# fullstack_dl
Full stack deep learning starter kit


# commands

- Install pre-commit via `pre-commit install` at the beginning. more about pre-commits [here]()
- `docker run -it pl:v01 /bin/bash` to run the docker in an interactive mode
-  `docker build --tag pl:v01 .` to build the image
- `docker run --gpus all -it pl:v01 /bin/bash` to run docker image so that docker can use gpus.
- `jupyter notebook --allow-root` to run jupyter notebook inside the docker.


## Things to work on
- [ ] nbdev and its uses.
- [ ] setup your terminal using - ZSH
- [ ] setting up docker and vscode for remote container.
- [ ] classification using pytorch lightning.
- [ ] writing pytest.
- [ ] Github actions.
- [x] pre-commit hooks and its uses. [issue#6](https://github.com/prakashjayy/fullstack_dl/issues/6)
- [ ] Github CI/CD pipeline.
- [ ] setting up DVC or Git-LFS.
- [ ] setting up mlflow/wandb.
- [ ] writing apis using fastapi.
- [ ] quantization/fp16/int8 calibration.
- [ ] onnx.
- [ ] tensorrt.
- [ ] deploying on edge device.


## Resources
- [Facebook Research about Pytorch Lightning](https://ai.facebook.com/blog/reengineering-facebook-ais-deep-learning-platforms-for-interoperability)
- [ ] tensorrt.
- [ ] streamlit
- [ ] deploying on edge device.
