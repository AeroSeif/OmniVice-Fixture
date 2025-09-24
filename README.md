# OmniVice – Modular 3D-Printed Clamping Fixture

A parametric **3D-printed modular fixture** designed to act as an *OmniVice* for inspection and prototyping setups.  
The fixture uses **three identical printed brackets**, which, when clamped, can grip parts of almost any geometry — from shafts to irregular profiles.

---

## Purpose

In precision manufacturing, flexible fixturing saves time and eliminates the need to design a unique fixture for every part.  
This project demonstrates how a simple 3D-printed solution can:
- Hold round or irregular parts securely
- Support inspection tasks and offline programming
- Speed up setup time and reduce waste (Lean principle: **setup time reduction**)

---

## Features

- ✅ **Parametric design** – easily scale bracket size for larger or smaller parts  
- ✅ **Quick setup** – just 3D-print, clamp, and start inspecting  
- ✅ **Reusable** – same brackets work for multiple parts and configurations  
- ✅ **Cost-effective** – minimal material and fast print time  

---

## Screenshots

**OmniVice Setup – Clamping Example**
![OmniVice Assembly](Media/OmniVice_Assembly.png)

**Single Bracket Design**
![Bracket Close-Up](Media/Bracket_CloseUp.png)

---

## CAD Files Structure

| Path / File              | Description                  |
|------------------------|------------------------------|
| **OmniVice.SLDASM**    | Main assembly file           |
| **Bracket.SLDPRT**     | Parametric 3D-printed bracket |
| **Clamp.SLDPRT**       | Fixture clamp                |
| **Clamp Handle.SLDPRT**| Handle for tightening         |
| **Vice Body.SLDPRT**   | Base body of the vice         |
| **Bolt.SLDPRT**        | Fasteners                    |
| **Sample Part.SLDPRT** | Example part (bottle)        |

---

## How to Use

1. **Open Assembly:**  
   `OmniVice.SLDASM`

2. **3D Print:**  
   Export `Bracket.SLDPRT` as STL and print 3× (or more).

3. **Assemble & Clamp:**  
   Place brackets in the vice and clamp around the part to hold securely.

---

## License

Released under the **MIT License**.  
Forks, adaptations, and improvements are welcome.
