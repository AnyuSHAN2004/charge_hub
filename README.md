# CHARGE HUB（一分四 Type-C 充电座）

CHARGE HUB is a one-to-four USB Type-C charging dock designed to keep multiple devices organized and powered from a single hub.

CHARGE HUB 是一款一分四 USB Type-C 充电座，可通过一个充电座同时为多台设备充电并保持桌面整洁。

<img width="1707" height="1280" alt="charge_hub_demo" src="https://github.com/user-attachments/assets/ac45f446-fa01-4a9a-83fe-0cef444e7e5e" />

All PCB design files are located in the `/PCB` folder. To fabricate the PCB directly, upload `Charge_Hub_V1.zip` to your PCB manufacturer. To view or modify the design, open the source files using Altium Designer.

所有 PCB 设计文件均位于 `/PCB` 文件夹中。如需直接打样，请将 `Charge_Hub_V1.zip` 上传至 PCB 制造商。如需查看或修改设计，请使用 Altium Designer 打开源文件。

All 3D files are located in the `/3D` folder. Submit either the `.step` or `.stl` file to a manufacturer, or use the `.stl` file with your own 3D printer, to produce the enclosure directly.

所有 3D 文件均位于 `/3D` 文件夹中。你可以将 `.step` 或 `.stl` 文件提交给制造商，也可以使用 `.stl` 文件通过自己的 3D 打印机直接制作外壳。

If you would like to design your own enclosure, edit the `.f3d` file in Fusion 360 or start from scratch using the PCB outline and mounting-hole positions provided in `charge_dock_pcb_ref.dxf`. Please note that the DXF file does not include other components, so make sure your design leaves enough clearance for components on the bottom side of the PCB.

如需自行设计外壳，可以使用 Fusion 360 编辑 `.f3d` 文件，也可以参考 `charge_dock_pcb_ref.dxf` 中提供的 PCB 外形和安装孔位从头开始设计。请注意，DXF 文件中未包含其他元器件，因此设计时请为 PCB 底面的元器件预留足够空间，避免发生干涉。

Feel free to build, modify, and improve this project. Contributions and suggestions are always welcome—let’s make life better together!

欢迎制作、修改和改进本项目，也欢迎提出建议或贡献内容。让我们一起让生活变得更美好！
