Device Failure Visualization (WPF)

Project

This is a WPF application written in C# designed for visualizing device failures on a pixel-based canvas. The application analyzes device failure data and visualizes devices with serious failures on the canvas using different colors.

Features

The application analyzes device failures using Device, Failure, and ReportMaker classes.
Data visualization of failures on a WPF canvas.
Devices with serious failures are displayed in red.
Project Structure

DeviceFailureProject/
│
├── Models/
│   ├── Device.cs
│   ├── Failure.cs
│   └── ReportMaker.cs
│
├── MainWindow.xaml
├── MainWindow.xaml.cs
├── App.xaml
├── App.xaml.cs
├── DeviceFailureProject.csproj
└── README.md
How to Run

Install Visual Studio 2022+ with the .NET Desktop Development workload.
Clone or download the project:
git clone https://github.com/YOUR_USERNAME/DeviceFailureProject.git
Open the project in Visual Studio.
Build and run the project.
How Visualization Works

Each device is represented as a pixel on the canvas.
Devices with serious failures are shown in red.
Other devices are displayed in gray.
Technologies Used

C#
WPF (.NET)
XAML
Encapsulation principles and working with collections
Author

Project created by: Aiturgan Tuuganbekova
Year: 2025

