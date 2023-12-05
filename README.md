# What is this about?
This repository contains sources of a program demonstrating issues of non-uniform frame pacing, through colour flickering.

---

# Build instructions

1. Open terminal in directory, where you want to place the project and clone the repository with:

```
git clone https://github.com/WojciechCzechowski-SmartFrame/ColourFlicker_SDL2_linux
```

---

2. Install SDL2 library on your linux machine with:

```
sudo apt-get install libsdl2-dev
```

---

3. Verify, if you have **`g++`** command installed in your system with

```
g++ --version
```

If not, install it with

```
sudo apt install g++
```

---

4. Verify, if you have **`make`** command installed in your system with

```
make --version
```

If not, install it with

```
sudo apt install make
```

---

5. Navigate to directory where the cloned repository is located and start the build with

```
make
```

---

6. After succesfull build, run the app with

```
./main
```
