# solana_notebook
My exploration of solana
Create wallet:
solana-keygen grind --starts-with bos:1
solana config set --keypair bosy1VC2BH2gh5fdXA3oKn53EuATLwapLWC4VR2sGHJ.json
solana config set --url devnet
solana config get
spl-token create-token --enable-freeze --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb --enable-metadata mnt75nPc893Ewtc3qEaisGXGgr4sZfP41FvLgGLrTHJ.json
spl-token initialize-metadata mnt75nPc893Ewtc3qEaisGXGgr4sZfP41FvLgGLrTHJ 'uponly' 'UP'
