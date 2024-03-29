

<div align="center">
<img src="https://play-lh.googleusercontent.com/b5rTCsOUSkrwQTznCDQh1uKolRKmGLXqKLVqlMb0n4_1_QVEeLK63qA6P2nwnKxP_kA" alt="drawing" width="200"/>
  
<br/>
<br/>
<br/>

# Ambulance & Trucks Detection
Technical Assessment Submission
</div>

* Live Demo Interface: https://mrneuralnet-tech-assessment-kecilin.hf.space/
* Solution: https://docs.google.com/document/d/1byOo0ORWWNT-isihYCadRm3K7LU5r41TxQidhQ0yuDQ/edit?usp=sharing
* Training Report: https://api.wandb.ai/links/nodeflux-internship/eiwjg81c

# How to run yourself

### Install
1. `https://github.com/manfredmichael/tech-assessment-ai-engineer.git`
2. `pip install -r requirements.txt`. Note: You might want to activate your virtual environment first.
3. `streamlit run app.py`

### Inference

Inference on image:
```python pipelines.py --input_type image --path <image_path>```

Inference on video:
```python pipelines.py --input_type video --path <video_path>```

