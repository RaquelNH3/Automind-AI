# Car-AI
## AutoMind: A Privacy-First In-Car AI Assistant

**By Raquel Hernandez**

## Overview
AutoMind is a next-generation in-car AI assistant designed to make driving safer, calmer, and more intuitive. It combines a natural conversational interface with a hybrid LLM architecture that prioritizes privacy, low latency, and reliable assistance.

## Problem
Current in-car assistants are often limited to rigid voice commands, while many drivers rely on smartphones for navigation and information. This increases distraction and raises concerns about privacy and data security.

## Solution
AutoMind is a privacy-first conversational AI assistant that:

- Provides natural voice interaction
- Reduces driver distraction through hands-free assistance
- Handles routine requests locally with an on-device LLM
- Uses a cloud LLM only for complex reasoning when necessary
- Protects user data through privacy-first system design
- Supports a calmer driving experience with contextual assistance

## System Goals

**Primary Goal**
- Reduce driver workload and improve road safety

**Secondary Goals**
- Personalization
- Privacy protection
- Offline resilience
- Low-latency responses

## System Architecture

The AutoMind architecture includes:

- Wake Word Engine
- Speech-to-Text (STT)
- Context Manager
- On-Device LLM
- Optional Cloud LLM
- Retrieval-Augmented Generation (RAG) for vehicle manuals and navigation data
- Privacy Layer
- Safety Layer
- Text-to-Speech (TTS)
- Audio Response through the infotainment system

The architecture prioritizes on-device processing whenever possible, using cloud services only for requests requiring additional knowledge or complex reasoning.

## LLM Configuration

- **Deployment:** Hybrid (On-device + Cloud)
  - Balances privacy, low latency, and advanced capabilities.
- **License Type:** Open Source
  - Supports on-device deployment and greater control over sensitive user data.
- **Temperature:** 0.2
  - Produces consistent, reliable responses while minimizing hallucinations.
- **Max Tokens:** 150
  - Keeps responses concise and reduces driver distraction.
- **Top-K Retrieval:** 3
  - Retrieves only the most relevant vehicle manual or navigation documents.
- **Fine-Tuning**
  - Vehicle manuals, safety guidelines, and common driving commands.

## Success Metrics

- Reduced driver touch interactions
- Task completion rate
- Intent recognition accuracy
- Offline success rate
- Privacy trust score

## Personal Vision

I designed AutoMind to demonstrate how AI can improve the driving experience without sacrificing privacy or safety. By combining local AI processing with cloud capabilities only when necessary, AutoMind provides a practical approach to building trustworthy, driver-focused intelligent assistants.

## Files

- Slide deck: https://canva.link/tfk3ihbd8yhi7po
- System architecture diagram: Included in the presentation
