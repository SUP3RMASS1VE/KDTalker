# KDTalker
![Screenshot 2025-04-02 152637](https://github.com/user-attachments/assets/3814b74a-a1d6-4354-9961-371dc94a5a60)


https://github.com/user-attachments/assets/7ae5c541-6e8b-4dbe-8afd-ae44d72c402a


## Audio-Driven Talking Portrait Generator

KDTalker is an AI model that animates a static portrait image based on audio input, creating realistic talking videos with natural head movements and expressions.

![KDTalker Demo](https://raw.githubusercontent.com/ChaolongYang/KDTalker/main/assets/demo.gif)

## Features

- Generate realistic talking videos from a single portrait image
- Natural head pose movements synchronized with speech
- Supports various audio formats (WAV, MP3)
- Easy-to-use web interface built with Gradio

## Installation
Install via [Pinokio](https://pinokio.computer).

1. One click launcher https://github.com/SUP3RMASS1VE/KD-Talker

2. Upload a portrait image showing a clear face

3. Upload an audio file (WAV or MP3 format recommended)

4. Click "Generate Video" and wait for processing to complete

5. The generated video will be displayed and available for download

## Tips for Best Results

- **Portrait image**: Use a clear, well-lit photo with the face clearly visible
- **Audio quality**: Use clean audio without background noise
- **Audio format**: 16kHz mono WAV files work best
- **Processing time**: Depends on audio length (~1-3 minutes for typical files)

## Troubleshooting

### Common Issues

- **Error when uploading audio**: Try converting your audio to WAV format with 16kHz sample rate
- **No face detected**: Ensure the portrait image has a clearly visible face
- **Low-quality output**: Use a higher resolution portrait image and clean audio
- **Out of memory error**: Try using shorter audio clips or reduce image resolution

## Model Information

KDTalker is based on "Unlock Pose Diversity: Accurate and Efficient Implicit Keypoint-based Spatiotemporal Diffusion for Audio-driven Talking Portrait" research. The model uses:

- Diffusion models for keypoint prediction
- Wav2Lip for audio-visual synchronization
- 3D face reconstruction for realistic movements

## Credits

- KDTalker model by Chaolong Yang et al.
- Gradio for the web interface
- Wav2Lip for audio-visual synchronization

## License

Please refer to the original model license on the [KDTalker GitHub repository](https://github.com/ChaolongYang/KDTalker). 
