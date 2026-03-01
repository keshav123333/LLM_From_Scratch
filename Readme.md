
# Create dataset











# Torch genral commab
## 1 torch emb
     pos_emb=torch.nn.Embedding(4,10)
  emb ko like dekh aise hi ni sakte as pos_emb embedding(4,10) ka ispe .shape bhi not work na hi iterate
  
    pos_emb1=pos_emb(torch.arange(0,4)) #isko iterate ke liye isko call with andar tensor with index jo chaiye torch arange [0,1,2,3] aise tenso bana degi
