# Blazor SignalR Chat App

This is a real-time chat application built using **ASP.NET Core**, **Blazor Server**, and **SignalR**. It demonstrates how to enable instant client-server communication in a modern web app using .NET technologies.

---

## 💡 About the Project

This application showcases how to:

- Integrate SignalR into a Blazor Server app.
- Handle real-time messaging between multiple users.
- Use Razor components to structure a responsive, interactive chat interface.

Whether you're exploring real-time web features or learning about full-stack .NET development, this project offers a solid starting point.

---

## ⚙️ Tech Stack

- **ASP.NET Core 9.0**
- **Blazor Server**
- **SignalR**
- **C#**
- **Bootstrap**

---

## 🖼️ App Overview

- **Real-Time Messaging**: Messages sent from one client are instantly broadcast to all others using SignalR.
- **Server-Side Blazor**: UI is rendered on the server and updated efficiently via SignalR connections.
- **Component-Based UI**: Built with reusable Razor components for modularity and maintainability.

---

## 📁 Project Structure

BlazorSignalRApp/

├── Pages/ # Razor pages (Chat, Home, etc.)

├── Components/ # Reusable UI components

├── Hubs/ # SignalR hub logic

├── wwwroot/ # Static assets (CSS, JS)

├── Program.cs # Application setup

├── App.razor # Routing and layout

└── BlazorSignalRApp.csproj


---

## 🚀 How to Run

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/)
- Visual Studio 2022 or VS Code with C# extensions

### Steps

```bash
# Clone this repository
git clone https://github.com/MeghanaB28/ASP.NET-Core-SignalR-with-Blazor-.git

# Navigate into the project folder
cd ASP.NET-Core-SignalR-with-Blazor-

# Run the application
dotnet run

Then open https://localhost:5001 in your browser to test the real-time chat!
