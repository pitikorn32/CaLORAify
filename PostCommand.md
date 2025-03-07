1. update linux
```bash
apt update && apt upgrade -y
```

2. install OpenCV env
```bash
apt update && apt install -y python3-opencv
```

3. create conda env
```bash
conda create -n minigptv python=3.9
conda activate minigptv
```

4. install pytorch
```bash
pip install torch torchvision torchaudio
```

5. install requirements.txt
```bash
pip install -r requirements.txt
```