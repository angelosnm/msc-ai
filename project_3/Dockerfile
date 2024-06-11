FROM quay.io/jupyter/pytorch-notebook:cuda12-python-3.11

# llama.cpp installation
RUN git clone https://github.com/ggerganov/llama.cpp.git \
    && cd llama.cpp \
    && make 

# llama-2-7b download
RUN mkdir -p /home/jovyan/llama.cpp/models/llama-2-7b \
    && wget https://huggingface.co/TheBloke/Llama-2-7B-GGUF/resolve/main/llama-2-7b.Q4_K_M.gguf -P /home/jovyan/llama.cpp/models/llama-2-7b
