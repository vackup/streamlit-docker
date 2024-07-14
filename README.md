# Sample streamlit python containerized app using docker

Based on:
- https://code.visualstudio.com/docs/python/python-tutorial
- https://www.freecodecamp.org/news/python-requirementstxt-explained/
- https://docs.streamlit.io/get-started/tutorials/create-an-app?ref=robkerr.ai
- https://code.visualstudio.com/docs/containers/quickstart-python
- https://robkerr.ai/publish-streamlit-app-docker-azure-container/

## Docker image
To build docker image:
```
docker build -t streamlit .
```

To run container:
```
docker run -p 8501:8501 streamlit
```

And then go to:
```
http://localhost:8501/
```
