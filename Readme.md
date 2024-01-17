# Overview

This repository contains a set of Jupyter Notebooks created to explain some fundamentals of Software Defined Radio (SDR) and how Digital Signal Processing can be used to analyze and synthesize radio signals.

The material is split into three notebooks:

## Part 1: SDR Basics

This notebook explores some of the fundamental concepts about radio signals, modulation and demodulation, mixing, quadrature signals, etc.

## Part 2: FM Demodulation Demonstration (TODO)

This notebook uses IQ samples acquired from an RTL-SDR dongle to demodulate and playback audio from FM broadcast radio stations. It demonstrates filtering, decimation, and FM demodulation.

## Part 3: BPSK Demodulation Demonstration (TODO)

This notebook uses the same broadcast FM IQ data collected in the Part 2 notebook, but this time focuses on demodulating the digital RDS subcarrier that contains station information. This requires timing synchronization, frequency recovery, BPSK demodulation, differential Manchester decoding, error detection, and protocol decoding.

# Requirements

These Notebooks are intended to run in Jupyter Notebook 7. If using the Anaconda Python distribution, you will likely need to upgrade your Jupyter Notebook version and also install the `ipympl` package.
