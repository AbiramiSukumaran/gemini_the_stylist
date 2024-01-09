# Gemini, the stylist
Like me, are you an AI enthusiast who is tired of the same old hairstyle and looking for a fresh change in a fresh year? Imagine having an AI-powered stylist at your fingertips, ready to recommend the perfect haircut based on your face shape.

# Before I begin: 
Opinions, ideas, and examples shared in this blog are entirely my own, shaped by personal interests and experiences. They do not reflect the views of my employer, any other company, or individuals. This experiment is purely driven by my curiosity and passion. The context and image samples provided are intended for educational purposes only and should not be considered within a commercial context. The background context is curated based on my knowledge and gathered information about hairstyles, making responses highly subjective. As a result, this app has not been deployed, emphasizing its experimental nature.

# Introduction
I was bored and needed a haircut. Decided to Gemini my way through the new look. Like me, are you an AI enthusiast who is tired of the same old hairstyle and looking for a fresh change in a fresh year? Imagine having an AI-powered stylist at your fingertips, ready to recommend the perfect haircut based on your face shape. 

# What are we building?
A Python program that leverages the power of Gemini Pro Vision and Imagen 2 to generate personalized haircut suggestions. From identifying face shapes to suggesting hairstyles, this cutting-edge approach combines the strengths of text and image generation models. Let's dive into the technical details behind this AI-driven makeover!

# How are we building?
Gemini Pro Vision generative model!!! It is Google's multimodal generative AI model that accepts text, images and videos as input and generates text in response. We will use 
Google Cloud's Vertex AI Gemini API that provides a unified interface to interact with the Gemini models. In order to invoke the Vertex AI Gemini API, we will use the Vertex AI SDK for Python.
Imagen 2 to generate images (of models sporting hairstyles) based on the prompt that is generated as your recommendation
I have created a knowledge base pdf as context, based on publicly available articles on haircuts for face shapes. I have used Imagen 2 generated images for sample face shape outlines. Sources are listed here with links to references.

# Why Gemini?
Great question! I like the fact that I am able to send multi-modal input (text, images and more text) as input all in the same request and get the response in a format that I am able to even programmatically control. For instance, JSON. Of the many things I like about Gemini, this one stood out during this experiment.

# Code
Available in this blog:
[https://medium.com/@abidsukumaran/gemini-the-stylist-5bf20c808493](url)

