********Net Information********

ObsQBNet(
  (encoder): Sequential(
    (0): Linear(in_features=200, out_features=800, bias=True)
    (1): Tanh()
    (2): Linear(in_features=800, out_features=100, bias=True)
    (3): TernaryTanh()
  )
  (decoder): Sequential(
    (0): Linear(in_features=100, out_features=800, bias=True)
    (1): Tanh()
    (2): Linear(in_features=800, out_features=200, bias=True)
    (3): ReLU6()
  )
)

INFO:
time_taken : 1462.0762
