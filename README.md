#  Ball Burnishing of Laser Cladded SS316L Surface🛠️

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scanning%20Electron%20Microscopy%20(SEM)-00BFFF?logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Optical%20Microscopy-4A7043?logo=materialdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/Contact%20Profilometer-2E8B57?logo=standard&logoColor=white" />
  <img src="https://img.shields.io/badge/Ball%20Burnishing-FF6F00?logo=3dprinter&logoColor=white" />
  <img src="https://img.shields.io/badge/Materials%20Science-8B4513?logo=materialdesign&logoColor=white" />
</p>

---

This project investigates the ball burnishing process on laser cladded SS316L surfaces (1-layer and 5-layer) and bulk material. The study examines the effect of feed rate on surface roughness (Ra, Rz) and bearing parameters after turning and ball burnishing operations.

## 1. Introduction

Ball burnishing, a post-machining technique, assumes a pivotal role in enhancing the surface characteristics and mechanical properties of machined metallic components. Employing a ball typically crafted from materials such as aluminium carbide, cemented carbide, or silicon nitride, under emulsion pressure, spanning a range of 80 to 200 bar. The ball’s methodical rolling action across the surface, coupled with the application of a normal force exerts a pressure which impacts the surface integrity of a substrate. These enhancement signatures include induced plastic deformation, improved compressive residual stress and geometric parameters, notably surface roughness. The resultant synergy of these refinements collectively contributes to a substantial augmentation in the fatigue life of the treated metallic components.

![Ball Burnishing Schematic](https://github.com/wisemansg/ballfinishing/raw/main/assets/A%20schematic%20representation%20of%20ball%20burnishing%20.jpeg)

**Figure 1**: A schematic representation of ball burnishing

## 🎯 2. Objectives

The aim of this practical session is to control the roughness of the material SS 316L, deposited by laser cladding and cold spraying with the following objectives:
- Understanding how ball burnishing process works.
- To investigate the effect of ball burnishing on the surface roughness of laser-clad stainless steel 316L.
- To investigate the influence of feed rate of the ball burnishing process on the surface roughness of laser clad stainless steel.

## 🛠️ 3. Materials and Methods

![Ecoroll Tool](https://github.com/wisemansg/ballfinishing/raw/main/assets/Ecoroll%20Tool%20Information..jpeg)

**Figure 2**: Ecoroll Tool Information

**Table 1: Process Parameters for Ball Burnishing Operation**

| Parameter      | Unit    | Value |
|----------------|---------|-------|
| Speed          | mm/min  | 120   |
| Load           | N       | 250   |
| Ball Diameter  | mm      | 6     |
| Pressure       | bar     | 100   |

**Table 2: Process Parameters for Turning Operation**

| Parameter                  | Unit     | Value |
|----------------------------|----------|-------|
| Cutting Speed Vc           | mm/min   | 120   |
| Feed (f)                   | mm/rev   | 0.2   |
| Depth of cut (ap) for Bulk | mm       | 0.2   |
| Depth of cut (ap) for 5 layer | mm    | 1     |
| Depth of cut (ap) for 1 layer | mm    | 0.5   |

![Cold Sprayed Specimen](https://github.com/wisemansg/ballfinishing/raw/main/assets/Cold-sprayed%20specimen%20after%20several%20turning%20process..jpeg)

**Figure 3**: Cold-sprayed specimen after several turning processes

## 📊 4. Results and Discussion

### 4.1 Analysis of Laser Cladded 1-Layered Specimen

**Table 3: Experimental and theoretical Ra values for ball burnishing**

| Test | Feed (mm/rev) | ap (mm) | Vc (mm/min) | Ra(µm) | Ratheo µm | Variation % |
|------|---------------|---------|-------------|--------|-----------|-------------|
| 1    | 0.17          | 1       | 120         | 0.276  | 0.309     | 11          |
| 2    | 0.17          | 1       | 120         | 0.258  | 0.309     | 17          |
| 3    | 0.17          | 1       | 120         | 0.258  | 0.309     | 17          |
| 4    | 0.05          | 1       | 120         | 0.243  | 0.0267    | 809         |
| 5    | 0.05          | 1       | 120         | 0.245  | 0.0267    | 817         |
| 6    | 0.05          | 1       | 120         | 0.198  | 0.0267    | 641         |
| 7    | 0.2           | 1       | 120         | 0.310  | 0.428     | 28          |
| 8    | 0.2           | 1       | 120         | 0.330  | 0.428     | 23          |
| 9    | 0.2           | 1       | 120         | 0.304  | 0.428     | 29          |
| 10   | 0.1           | 1       | 120         | 0.080  | 0.107     | 25          |
| 11   | 0.1           | 1       | 120         | 0.074  | 0.107     | 31          |
| 12   | 0.1           | 1       | 120         | 0.066  | 0.107     | 38          |

As we can see from the Table 3; the theoretical Ra values are matching with the experimental Ra values. But, on test numbers 4, 5, and 6 which have feed rates of 0.05 mm/rev, there is a large difference between theoretical and experimental values. Our experimental values were significantly higher than the theoretical values. This was unexpected. We think that the reason for this big difference is laser cladding creates a non-homogeneous surface. In addition, the reason for the low roughness values in the tests performed with 0.1 mm/rev feed rate is that the measurement length of the stylus profilometer for those readings were smaller compared to other measurements (3.5 mm instead of 4.8 mm).

**Table 4: Experimental and theoretical Ra values for turning**

| Test | Feed (mm/rev) | ap (mm) | Vc (mm/min) | Ra(µm) | Ratheo (µm) | Variation % |
|------|---------------|---------|-------------|--------|-------------|-------------|
| 1    | 0.2           | 1       | 120         | 1.945  | 1.604       | 21          |
| 2    | 0.2           | 1       | 120         | 1.783  | 1.604       | 11          |
| 3    | 0.2           | 1       | 120         | 1.846  | 1.604       | 15          |
| 4    | 0.2           | 1       | 120         | 1.729  | 1.604       | 8           |
| 5    | 0.2           | 1       | 120         | 1.677  | 1.604       | 5           |
| 6    | 0.2           | 1       | 120         | 1.734  | 1.604       | 8           |

![Ra vs Feed - 1 Layer](https://github.com/wisemansg/ballfinishing/raw/main/assets/Ra%20vs%20feed%20rate%20graph%20for%20laser%20cladded%201-layer%20specimen..jpeg)

**Figure 4**: Ra vs feed rate graph for laser cladded 1-layer specimen

![Rz vs Feed - 1 Layer](https://github.com/wisemansg/ballfinishing/raw/main/assets/Rz%20vs%20feed%20rate%20graph%20for%20laser%20cladded%201-layer%20specimen..jpeg)

**Figure 5**: Rz vs feed rate graph for laser cladded 1-layer specimen

![Surface Parameters - 1 Layer](https://github.com/wisemansg/ballfinishing/raw/main/assets/Surface%20parameters%20vs%20feed%20rate%20graph%20for%20laser%20cladded%201-layer%20specimen..jpeg)

**Figure 6**: Surface parameters vs feed rate graph for laser cladded 1-layer specimen

The same trend is followed for the Abbott-Firestone parameters (Rk, Rpk, and Rvk). The parameters decrease due to the ball burnishing compared to the turned sample. And as earlier observed for the Ra and Rz values, these parameters also initially decrease as the feed rate is reduced, but increase when the feed rate is further reduced from f=0.1 mm/rev to f=0.05 mm/rev. We propose the reason for the decrease in roughness parameters observed when the feed rate is further lowered is that the lower feed of 0.05 mm/rev does not affect the signature of the clad surface and therefore, the roughness does not decrease, but rather, increases.

### 4.2 Analysis of Laser Cladded 5-Layered Specimen

**Table 5: Experimental and theoretical Ra values for turning (5-layer)**

| Test | Feed (mm/rev) | ap (mm) | Vc (mm/min) | Ra(µm) | Ratheo (µm) | Variation % |
|------|---------------|---------|-------------|--------|-------------|-------------|
| 1    | 0.2           | 1       | 120         | 1.484  | 1.6038      | 7           |
| 2    | 0.2           | 1       | 120         | 1.473  | 1.6038      | 8           |
| 3    | 0.2           | 1       | 120         | 1.48   | 1.6038      | 8           |
| 4    | 0.2           | 1       | 120         | 1.815  | 1.6038      | 13          |
| 5    | 0.2           | 1       | 120         | 1.879  | 1.6038      | 17          |
| 6    | 0.2           | 1       | 120         | 1.875  | 1.6038      | 17          |
| 7    | 0.2           | 1       | 120         | 1.865  | 1.6038      | 16          |
| 8    | 0.2           | 1       | 120         | 1.837  | 1.6038      | 15          |
| 9    | 0.2           | 1       | 120         | 1.754  | 1.6038      | 9           |
| 10   | 0.2           | 1       | 120         | 1.716  | 1.6038      | 7           |
| 11   | 0.2           | 1       | 120         | 1.745  | 1.6038      | 9           |

**Table 6: Experimental and theoretical Ra values for ball burnishing (5-layer)**

| Test | Feed (mm/rev) | ap (mm) | Vc (mm/min) | Ra(µm) | Ratheo (µm) | Variation % |
|------|---------------|---------|-------------|--------|-------------|-------------|
| 1    | 0.05          | 1       | 120         | 0.303  | 0.0267      | 1034        |
| 2    | 0.05          | 1       | 120         | 0.283  | 0.0267      | 959         |
| 3    | 0.1           | 1       | 120         | 0.188  | 0.1069      | 76          |
| 4    | 0.1           | 1       | 120         | 0.162  | 0.1069      | 52          |
| 5    | 0.15          | 1       | 120         | 0.263  | 0.2406      | 9           |
| 6    | 0.15          | 1       | 120         | 0.287  | 0.2406      | 19          |
| 7    | 0.2           | 1       | 120         | 0.299  | 0.4277      | 30          |
| 8    | 0.2           | 1       | 120         | 0.324  | 0.4277      | 24          |
| 9    | 0.2           | 1       | 120         | 0.323  | 0.4277      | 24          |
| 10   | 0.2           | 1       | 120         | 0.3    | 0.4277      | 30          |
| 11   | 0.2           | 1       | 120         | 0.327  | 0.4277      | 24          |
| 12   | 0.1           | 1       | 120         | 0.289  | 0.1069      | 170         |
| 13   | 0.1           | 1       | 120         | 0.277  | 0.1069      | 159         |
| 14   | 0.1           | 1       | 120         | 0.28   | 0.1069      | 162         |

![Ra vs Feed - 5 Layer](https://github.com/wisemansg/ballfinishing/raw/main/assets/Ra%20vs%20feed%20rate%20graph%20for%20laser%20cladded%205-layer%20specimen..jpeg)

**Figure 7**: Ra vs feed rate graph for laser cladded 5-layer specimen

![Rz vs Feed - 5 Layer](https://github.com/wisemansg/ballfinishing/raw/main/assets/Rz%20vs%20feed%20rate%20graph%20for%20laser%20cladded%205-layer%20specimen..jpeg)

**Figure 8**: Rz vs feed rate graph for laser cladded 5-layer specimen

![Surface Parameters - 5 Layer](https://github.com/wisemansg/ballfinishing/raw/main/assets/Surface%20parameters%20vs%20feed%20rate%20graph%20for%20laser%20cladded%205-layer%20specimen..jpeg)

**Figure 9**: Surface parameters vs feed rate graph for laser cladded 5-layer specimen

### 4.3 Analysis of Substrate (Bulk) Surface

**Table 7: Experimental and theoretical Ra values for turning (bulk)**

| Test | Feed (mm/rev) | ap (mm) | Vc (mm/min) | Ra(µm) | Ratheo (µm) | Variation % |
|------|---------------|---------|-------------|--------|-------------|-------------|
| 1    | 0.2           | 1       | 120         | 3.646  | 1.604       | 127         |
| 2    | 0.2           | 1       | 120         | 3.267  | 1.604       | 104         |
| 3    | 0.2           | 1       | 120         | 4.084  | 1.604       | 155         |

**Table 8: Experimental and theoretical Ra values for ball burnishing (bulk)**

| Test | Feed (mm/rev) | ap (mm) | Vc (mm/min) | Ra(µm) | Ratheo (µm) | Variation % |
|------|---------------|---------|-------------|--------|-------------|-------------|
| 1    | 0.2           | 1       | 120         | 0.762  | 0.4277      | 78          |
| 2    | 0.2           | 1       | 120         | 0.51   | 0.4277      | 19          |
| 3    | 0.2           | 1       | 120         | 0.607  | 0.4277      | 42          |
| 4    | 0.1           | 1       | 120         | 0.289  | 0.1069      | 170         |
| 5    | 0.1           | 1       | 120         | 0.277  | 0.1069      | 159         |
| 6    | 0.1           | 1       | 120         | 0.28   | 0.1069      | 162         |

![Ra vs Feed - Bulk](https://github.com/wisemansg/ballfinishing/raw/main/assets/Ra%20vs%20feed%20rate%20graph%20for%20bulk%20specimen..jpeg)

**Figure 10**: Ra vs feed rate graph for bulk specimen

![Rz vs Feed - Bulk](https://github.com/wisemansg/ballfinishing/raw/main/assets/Rz%20vs%20feed%20rate%20graph%20for%20bulk%20specimen..jpeg)

**Figure 11**: Rz vs feed rate graph for bulk specimen

![Surface Parameters - Bulk](https://github.com/wisemansg/ballfinishing/raw/main/assets/Surface%20parameters%20vs%20feed%20rate%20graph%20for%20bulk%20specimen..jpeg)

**Figure 12**: Surface parameters vs feed rate graph for bulk specimen

Tests were also carried out on the bulk sample, which does not contain any cladding. While comparing the effect of ball burnishing to turning, it is observed that the roughness parameters all decrease for the burnished surface compared to the turned surface. The effect of changing the feed rates was also studied for two feed rates, f= 0.2 mm/rev and 0.1 mm/rev. By decreasing the feed rates, the roughness parameters were all observed to decrease.

### 4.4 Analysis of Cold-Sprayed Surface

Two types of materials (copper and stainless steel) were coated on to the aluminium substrate. After several turning trials smooth surface could not be obtained. This is because during cold spray, the coating becomes very hard due to the high deformation. Even though turning was tried many times with different parameters, they all failed. A smooth surface could not be obtained and the cutting tool broke. Therefore it could not be machined unless prior heat treatment was done. Due to the lack of time the heat treatment process could not done.

## 🚀 Applications of Ball Burnishing

- Enhancement of surface finish and fatigue life of high-value components
- Post-processing of laser cladded and cold sprayed surfaces
- Aerospace, automotive, and precision engineering applications

## 📌 5. Conclusions

The experiments were carried out to study the ball burnishing process, to understand the effect of ball burnishing a surface compared to turning, and the effect of varying the feed rates for the ball burnishing. When ball burnishing is carried out, all the roughness parameters studied (Ra, Rz, Rk, Rpk, Rvk) decreased compared to the sample on which only turning was done. This is expected from the process, as it deforms and smoothens the surface. Theoretically, the roughness parameters are expected to decrease when the feed rate for ball burnishing is lowered. This was observed for some feed rates. However, on the experiments done on the laser clad samples, there is an increase in the roughness parameters when the feed was decreased to 0.05 mm/rev. This is attributed to the feed not affecting the signature of the clad surface due to the inherent non-homogeneous nature of the laser cladding process. To conclude, ball burnishing is an excellent process to utilize to obtain good surface finish. However, more tests could be done at lower feed rates in the future to conclude properly about the deviation from the theoretical roughness that is observed at lower feeds.

## 🛠️ Tools & Methods Used

- CNC Lathe with Ecoroll Ball Burnishing Tool
- Contact Profilometer
- Python for data analysis

