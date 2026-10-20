<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Hi, I'm Loukas Pavlou. SQL and Oracle APEX developer, building robot autonomy in C++ and ROS 2." width="100%">
</picture>

Software developer at **Allianz Greece**, working mainly with **SQL, PL/SQL and Oracle APEX**.
I'm moving into **robotics**: my recent projects are mobile-robot autonomy stacks in **C++** and
**ROS 2**, one with every algorithm written from scratch, one built on the industry stack (Nav2,
Gazebo, behavior trees), both tested in CI and documented down to the bugs I hit.
Before that, Python apps and machine-learning research tools that answer a real question:
*what's worth watching tonight?*, *does this trading idea survive real costs?*

🌐 **[turnedone.github.io](https://turnedone.github.io)** · 💼 [LinkedIn](https://www.linkedin.com/in/luke-pavlou-753104219/) · ✉️ [loukas.pavlou11@gmail.com](mailto:loukas.pavlou11@gmail.com) · 📍 Greece

## 🤖 Robotics

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Turnedone/warehouse-delivery-robot">
        <img src="https://raw.githubusercontent.com/Turnedone/warehouse-delivery-robot/main/docs/images/run_trajectory.png" alt="Paths driven by the warehouse robot, one colour per order">
      </a>
      <h3><a href="https://github.com/Turnedone/warehouse-delivery-robot">Warehouse delivery robot</a></h3>
      A TurtleBot 4 takes delivery orders from a queue and drives them from shelves to packing stations
      through a simulated warehouse with keep-out zones, slow zones and a moving forklift, then docks
      to charge when its battery runs low. Built the way a warehouse-automation team would:
      Nav2 (AMCL, MPPI, Smac, costmap filters, docking), a C++ mission layer on BehaviorTree.CPP,
      headless end-to-end tests, a KPI report computed from recorded rosbags.
      <br><br>
      <code>C++17</code> <code>ROS 2 Jazzy</code> <code>Nav2</code> <code>Gazebo Harmonic</code> <code>BehaviorTree.CPP</code> <code>Docker</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Turnedone/robot-sim">
        <img src="https://raw.githubusercontent.com/Turnedone/robot-sim/main/docs/images/navigation.png" alt="robot-sim planning through an unexplored maze">
      </a>
      <h3><a href="https://github.com/Turnedone/robot-sim">robot-sim</a></h3>
      A 2D mobile-robot simulator with the autonomy stack written from scratch: differential-drive
      kinematics, a noisy lidar, occupancy-grid mapping, A* and pure pursuit, particle-filter
      localization and GMapping-style SLAM. The same core also drives a TurtleBot 3 in Gazebo
      through ROS 2.
      <br><br>
      <code>C++17</code> <code>CMake</code> <code>GoogleTest</code> <code>ROS 2</code> <code>raylib</code>
    </td>
  </tr>
</table>

## 🚀 Other projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Turnedone/flixdex">
        <img src="https://raw.githubusercontent.com/Turnedone/flixdex/main/docs/screenshot.png" alt="Flixdex screenshot">
      </a>
      <h3><a href="https://turnedone.github.io/flixdex/">Flixdex</a></h3>
      Every Netflix &amp; HBO Max title in your country, with IMDb ratings, in one fast Windows app.
      Search, filters, sorting and one-click <i>Watch</i> links. Uses only free data sources with no daily limits.
      <br><br>
      <code>Python</code> <code>PySide6 / Qt</code> <code>TMDB</code> <code>IMDb datasets</code>
      <br><br>
      <a href="https://github.com/Turnedone/flixdex/releases/latest"><b>⬇ Download for Windows</b></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Turnedone/edgelab">
        <img src="https://raw.githubusercontent.com/Turnedone/edgelab/main/docs/dashboard.png" alt="EdgeLab dashboard">
      </a>
      <h3><a href="https://turnedone.github.io/edgelab/">EdgeLab</a></h3>
      Does an intraday machine-learning stock strategy have a real edge after costs? A research system built to
      answer honestly: walk-forward validation, realistic costs, random baselines, Deflated Sharpe and an
      interactive virtual-money dashboard. (So far, the answer is no.)
      <br><br>
      <code>Python</code> <code>scikit-learn</code> <code>LightGBM</code> <code>pandas</code>
    </td>
  </tr>
</table>

### Also

- **[computational-intelligence](https://github.com/Turnedone/computational-intelligence)**: predicting MovieLens ratings with a neural network and a genetic algorithm. University coursework from 2020, cleaned up, bug-fixed and tested.

## 🧰 Tools I use

**Robotics:**
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS%202%20Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-2C3E50?style=flat-square)
![Gazebo](https://img.shields.io/badge/Gazebo%20Harmonic-F58113?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux%20%2F%20WSL2-FCC624?style=flat-square&logo=linux&logoColor=black)

**Data and apps:**
![SQL](https://img.shields.io/badge/SQL%20%2F%20PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)
![Oracle APEX](https://img.shields.io/badge/Oracle%20APEX-C74634?style=flat-square&logo=oracle&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Qt](https://img.shields.io/badge/Qt%20%2F%20PySide6-41CD52?style=flat-square&logo=qt&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

<sub>Found a bug or have an idea for one of these? Open an issue on the project. I read them all.</sub>
