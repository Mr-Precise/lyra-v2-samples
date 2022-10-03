# Lyra V2 audio test samples for opennet.ru telegram discussion

A Very Low-Bitrate Codec for Speech Compression  
https://github.com/google/lyra/  

Audio sample from `https://www.youtube.com/watch?v=ERLnYhPohMA` (Russian language) 

- Encode:  
`./encode-linux-static-x86_64 --input_path="/path/to/original-mono-16000.wav" --output_dir=/path/to/your/encode/dir/ --bitrate=3200`

- Decode:  
`./decoder-linux-static-x86_64 --encoded_path="/path/to/original-encoded-bitrate-3200.lyra" --output_dir=/path/to/your/decode/dir/ --bitrate=3200`
