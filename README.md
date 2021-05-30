# NVIDIA_NeMo_Voice_Swap
NVIDIA's NeMo and Pytorch Lighting API is used to load an audio_sample and convert it to text with QuartzNet ASR model. To convert text back to audio, spectrogram with Tacotron2 is generated first and then convert into actual audio signal using WaveGlow vocoder.
