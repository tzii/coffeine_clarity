# 🚀 Caffeine Clarity

Welcome to Caffeine Clarity, the ultimate tool for mastering your daily buzz! Ever wonder how that morning espresso or afternoon energy drink affects your system throughout the day? This app gives you the power to see your caffeine levels in real-time, helping you optimize your focus and protect your sleep.

This isn't just another boring tracker. It’s a sleek, modern Flutter application built with Material 3, designed to give you a dynamic and insightful look into your body's caffeine metabolism.

### ✨ Visualize Your Buzz

At the heart of Caffeine Flow is a gorgeous, interactive graph. It’s not a static image; it's a living representation of your caffeine journey. Watch as the curve rises during absorption and gently slopes downward as your body metabolizes it. The graph dynamically recalculates and redraws with every single drink you log, giving you an immediate and accurate picture of your state.

### ☕ Track Everything, Effortlessly

Life isn't just one cup of coffee. Log every espresso, tea, or soda you have throughout the day. The app intelligently stacks each intake, creating a composite graph that shows the total caffeine active in your system at any given moment. Made a mistake? No problem. Just tap an entry to edit the amount or time.

### 💾 Your Data, Saved Securely

Your caffeine log is your personal data, so it should never disappear. Caffeine Flow uses a powerful local Hive database to instantly save every change. Close the app, restart your phone—your entire history will be right there waiting for you, ready for your next entry.

### 🎨 Own Your Vibe

Your tools should match your style. The app defaults to a beautiful, custom brown color scheme inspired by a perfect cup of coffee. But why stop there? With a simple toggle, you can unleash the power of Material You and have the app's entire color palette adapt to your phone's wallpaper. For even more control, a full color picker lets you choose a theme that’s uniquely you.

### 😴 Plan Your Sleep

Take the guesswork out of your evening wind-down. The app analyzes your intake and calculates an estimated "clearance time"—the moment your body will be effectively free of caffeine's effects. It even provides a gentle warning if your last cup might interfere with your target bedtime, empowering you to make smarter choices for better rest.

## Getting Started

Ready to build and run the project yourself? It's simple.

First, ensure you have the Flutter SDK set up on your machine. Clone the repository, and then from the project's root directory, run `flutter pub get` to install all the necessary dependencies.

Because this project uses the Hive database for local storage, we rely on code generation to create necessary helper files. Run the following command in your terminal to generate them:

`flutter pub run build_runner build --delete-conflicting-outputs`

Once that completes successfully, you can launch the app on your connected device or emulator with a final `flutter run` command. Enjoy the flow
