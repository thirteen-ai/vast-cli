# vast-cli
copy 명령어에 --exclude 가 없어서 추가하였음

### vast-cli install
```
wget https://raw.githubusercontent.com/thirteen-ai/vast-cli/master/vast.py -O vast; chmod +x vast;
```

### example
1. copy
```
vast copy {src} {machine_id}:/root -i ~/.ssh/id_ed25519 --exclude "{'*.pyc','*.log','.result','wandb','.idea','.git','*pycache*','temp'}"
```

