# MB-GMN
Code for MB-GMN, SIGIR 2021

For Beibei data, run
```
python .\labcode.py
```

For Tmall data, run
```
python .\labcode.py --data tmall --rank 2
```

For IJCAI data, run
```
python .\labcode_samp.py --data ijcai --rank 2 --graphSampleN 40000
```

## Project structure
```
.
├── [5.5K]  DataHandler.py
├── [ 65M]  Datasets
│   ├── [ 26M]  beibei
│   │   ├── [2.2M]  trn_buy
│   │   ├── [5.0M]  trn_cart
│   │   ├── [ 18M]  trn_pv
│   │   └── [275K]  tst_int
│   ├── [4.1K]  ijcai
│   │   └── [  71]  readme.txt
│   └── [ 39M]  Tmall
│       ├── [5.5M]  trn_buy
│       ├── [5.7M]  trn_cart
│       ├── [2.6M]  trn_fav
│       ├── [5.0M]  trn_pv.part01.rar
│       ├── [5.0M]  trn_pv.part02.rar
│       ├── [5.0M]  trn_pv.part03.rar
│       ├── [5.0M]  trn_pv.part04.rar
│       ├── [5.0M]  trn_pv.part05.rar
│       ├── [411K]  trn_pv.part06.rar
│       └── [168K]  tst_int
├── [362K]  images
│   ├── [349K]  mbgmn_model.png
│   └── [9.8K]  process_flow.svg
├── [ 14K]  labcode.py
├── [ 16K]  labcode_samp.py
├── [ 75K]  nbs
│   └── [ 71K]  P197505_MB_GMN_on_BeiBei.ipynb
├── [2.9K]  Params.py
├── [ 255]  README.md
├── [9.8K]  reports
│   └── [5.8K]  S346877_report.ipynb
└── [ 19K]  Utils
    ├── [1.1K]  DataProcessor.py
    ├── [1.0K]  FilterUnshown.py
    ├── [7.4K]  NNLayers.py
    ├── [ 943]  Plotter.py
    ├── [ 467]  SampleReader.py
    ├── [1.1K]  TimeLogger.py
    └── [2.7K]  VectorVisualization.py

  66M used in 8 directories, 31 files
```