# Taichi Example: Volume Rendering
## Introduction
This article implements a simple medical image volume rendering, achieving both maximum and minimum density projection algorithms. Projections can be performed from three different directions. Future enhancements may include adding blend modes and transfer functions.

## Structure (Optional)
```
├── data
│   └── FullHead.mhd
│   └── FullHead.raw.gz
├── README.md
├── volume_rendering.py
└── requirements.txt
```

## How to Run
Runtime Environment:

```
[Taichi] version 1.1.3, win, python 3.8.10
```

Ensure data and volume_rendering.py are in the same path, then run directly: python3 volume_rendering.py

Head data maximum density projection results from three directions:

![image](https://user-images.githubusercontent.com/9690396/195242213-cac9ba3d-204d-45b5-b581-e06223bc9024.png)
![image](https://user-images.githubusercontent.com/9690396/195242226-c9dc66ed-e66a-4ca0-bd45-28f772a60e83.png)
![image](https://user-images.githubusercontent.com/9690396/195242233-72c6857f-a04a-42a4-b454-5c575b855844.png)
