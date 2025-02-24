# UE-Camera-Validation

This project is designed to facilitate camera validation within Unreal Engine environments. It provides a laboratory room asset that can assist in testing and calibrating camera setups for various applications. 

![sim_setup](https://github.com/user-attachments/assets/4e33cf47-65bb-40d8-be3d-785d6b596b11)

**Note:** This project has been developed and tested using the ([AGRARSENSE Simulator](https://agrarsense.frostbit.fi/md_Docs_using_vehicles.html)) built on Unreal Engine 5 and evaluates the virtual camera from this simulator.

## Features

- **Blueprints**: Includes `BP_TestSetting.uasset` for customizable test configurations.
- **Materials**: Contains a ColorChecker test chart to assess camera colour accuracy.
- **Meshes**: Provides 3D models for scene setup and testing.
- **Sample Map**: `Lab_Room.umap` serves as a pre-configured environment for immediate testing.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:RISE-Dependable-Transport-Systems/UE-Camera-Validation.git
   ```
   Copy (or directly clone) the repository to the Unreal Engine project folder.

2. **Open the Project**:
   - Launch Unreal Engine.
   - Navigate to the cloned repository folder.
   - Open `Lab_Room.umap` to load the sample testing environment.
   - Open Level Blueprint and configure the default "Chart mesh map" variable to assign appropriate test chart static mesh to chart type.
     
     <p align="center">
      <img src=https://github.com/user-attachments/assets/25f19d6b-7f06-4aa1-b028-3ee6fc10c35e width="49.5%" />
    </p>


3. **Utilize Test Assets**:
   - Incorporate `BP_TestSetting.uasset` into your levels to configure camera tests.
   - Apply materials from the `Material` folder to meshes for visual validation.

## License

This project is licensed under the [GPL-3.0 license](LICENSE).

## Funded by

<img src="https://user-images.githubusercontent.com/2404625/202213271-a4006999-49d5-4e61-9f3d-867a469238d1.png" width="120" height="81" align="left" alt="EU logo" />
This project has received funding from the European Union’s Horizon Europe research and innovation programme under grant agreement nº 101095835. The results reflect only the authors' view and the Agency is not responsible
for any use that may be made of the information it contains.
