********Net Information********

HxQBNet(
  (encoder): Sequential(
    (0): Linear(in_features=32, out_features=512, bias=True)
    (1): Tanh()
    (2): Linear(in_features=512, out_features=256, bias=True)
    (3): Tanh()
    (4): Linear(in_features=256, out_features=64, bias=True)
    (5): TernaryTanh()
  )
  (decoder): Sequential(
    (0): Linear(in_features=64, out_features=256, bias=True)
    (1): Tanh()
    (2): Linear(in_features=256, out_features=512, bias=True)
    (3): Tanh()
    (4): Linear(in_features=512, out_features=32, bias=True)
    (5): Tanh()
  )
)

INFO:
time_taken : 2643.8312
