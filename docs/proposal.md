# RiseStake

_Stake crypto, shake your phone for 60 seconds, wake up or lose it_

## Summary

RiseStake is an alarm app where users stake SOL before sleeping. To silence the alarm, they must complete a 1-minute physical micro-challenge (rapid shake or squat count detected via phone sensors). Success returns the stake plus a share of forfeited stakes from people who failed; failure forfeits the stake to the daily winners' pool.

## Target users

People who can't wake up and want financial/physical pressure to get out of bed

## Problem

Traditional alarms are too easy to snooze and dismiss without actually waking up.

## Solution

Combine a short intense physical challenge with real financial stakes recorded on-chain to force genuine wake-up.

## MVP features

- Pre-sleep SOL staking via wallet connect
- Accelerometer-based 1-min shake/squat mini-game to disarm alarm
- Smart contract pool: failed stakes redistributed to successful wakers each day
- On-chain streak tracking and daily leaderboard
- Push notification + anti-cheat check (motion pattern validation)

## Chains

Solana

## Tech

React Native, Solana web3.js, Anchor, Phone accelerometer API, Supabase for off-chain motion logs, Solana Pay

## Category

Consumer

## Why now

Mobile-first fitness/accountability apps and crypto staking mechanics are converging, and fast Solana transactions make micro-stakes feasible.

## Roadmap

- Add anti-spoofing ML model for motion verification
- Launch squad/group staking mode
- Partner with fitness/insurance apps for streak-based perks
