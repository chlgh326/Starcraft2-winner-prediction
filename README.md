# Starcraft-2-winner-prediction

## Summary
Blizzard 스타크래프트2 경기의 행동 데이터로 승패를 예측합니다.

## Data collection
https://dacon.io/competitions/official/235583/overview/

## Final ranking (Team name: 동치미, 94팀 중 20위)
https://dacon.io/competitions/official/235583/leaderboard/

## My prediction model

Here's how I worked in the competition.

#### Table of contents
* [Loading Data](#1) 
* [Initial Exploration](#2) 
* [Data Cleansin](#3) 
* [Extra data for Feature engineering](#4) 
* [Feature engineering](#5) 
* [Data Preparation (Data Cleansing + Feature Engineering)](#6)
* [Data Partitionin](#7)
* [Modeling - light Gradient Boosting Machine (LGBM)](#8)
* [Feature Importance](#9)
* [Feature selection](#10)
* [Modeling - Multi Layer Perceptrons (MLP)](#11)
* [Performance evaluation of MLP](#12)
* [Submit Test Results](#13)
