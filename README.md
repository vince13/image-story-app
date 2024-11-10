# Image to Story Generator

This Streamlit application converts images into stories using AI. It:
1. Extracts a caption from the uploaded image
2. Generates a story based on the caption
3. Creates an audio narration of the story

## Models Used
- Image Captioning: Salesforce/blip-image-captioning-base
- Story Generation: gpt2
- Text-to-Speech: espnet/kan-bayashi_ljspeech_vits

## Usage
1. Upload an image
2. Click "Generate Story"
3. Wait for the caption, story, and audio to be generated
4. Download the audio narration if desired 