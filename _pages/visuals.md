---
layout: archive
title: "Visuals"
permalink: /visuals/
author_profile: true
---

{% include base_path %}

## Chronology of Binary Formation
Energetic evolutiion of a close encounter between two black holes embdedded in an AGN disc, simulation in 3D with a adiabatic gas equation of state. A stable binary is formed by dissipation to gas gravity during the first periapsis passes; during subseuquent passes the binary loses further energy to the gas and shrinks. Images in the top left panel produced using DART, a homebrew raytracing code in Python. Read the parent paper [here](/publication/Whitehead2025).

<video width="1000" height="1100" controls loop="" muted= "" autoplay ="">
    <source src="http://hwhitehead.github.io/images/fid_panel.mp4">
</video>

## Raytraced Emission from Supernova-Jet Interaction
Synthetic radio emission generated from axisymmetric relativistic hydrodynamic simulations of a supernovae followed by a jet, compared to real observations of CirX1. Axisymmetric data is interpolated onto a 3D Cartesian grid and then traced using DART. Parent paper is in the final stages of prep.

<p align="center">
  <img src="http://hwhitehead.github.io/images/novae_render.png"/>
</p>

## EXOTIC: Exoplanet Observables Translated Into Colour
A hobby project involving predicting exoplanet colours using synethetic spectra generated from known planetary properties. Planet colours were generated for the full NASA catalogue and then a custom-built C++ raytracing code rendered images of each star system. A Perlin noise map is imposed on each planetary surface to make for a more realistic texture.

<video width="1000" height="258" controls loop="" muted= "" autoplay ="">
    <source src="http://hwhitehead.github.io/images/55_Cnc_label.mp4">
</video>

A lightweight Python Tkinter GUI was also built to allow for easy system selection.
<video width="1000" height="344" controls loop="" muted= "" autoplay ="">
    <source src="http://hwhitehead.github.io/images/gui_demo.mp4">
</video>

## Radiative Binary Formation
Logarithmic thermal emission maps for an interaction between two black holes, for a 2D adiabatic mixture of gas and radiation. Each close encounter prompts a burst of thermal emission due to strong heating from the minidisc collisions. Read the parent paper [here](/publication/Whitehead2024b).

<video width="1000" height="980" controls loop="" muted= "" autoplay ="">
    <source src="http://hwhitehead.github.io/images/2d_flux.mp4">
</video>

## Isothermal Binary Formation
Logarithmic density maps for an interaction between two black holes embdedded in a 2D disc of isothermal gas. While no severe close encounter occurs, the binary is able to steadily loses energy due to the gas gravity, resulting in the formation of a stable, shrinking binary. Read the parent paper [here](/publication/Whitehead2024b).

<video width="1000" height="980" controls loop="" muted= "" autoplay ="">
    <source src="http://hwhitehead.github.io/images/2d_iso.mp4">
</video>
