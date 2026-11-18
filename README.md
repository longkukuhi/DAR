# Diffusion Augmented Retrieval (DAR)

DAR uses a dialogue and a diffusion-generated image to retrieve the photograph a user has in mind. The SIGIR 2025 paper evaluates this approach on interactive text-to-image retrieval without task-specific training. [Read the paper](https://doi.org/10.1145/3726302.3729950).

## Run the evaluation

The implementation lives in the companion repository. It contains the BLIP retrieval code, validation dialogues, the 50k-image candidate list and instructions for obtaining the weights and images. Use its evaluator to compare text-only retrieval with diffusion-augmented reranking. [Open the implementation and setup instructions](https://github.com/longkukuhi/Diffusion-Agumented-Retrieval).

## Citation

Zijun Long, Kangheng Liang, Gerardo Aragon Camarasa, Richard McCreadie and Paul Henderson. *Diffusion Augmented Retrieval: A Training-Free Approach to Interactive Text-to-Image Retrieval*. SIGIR 2025, pp. 823–832. [ACM Digital Library](https://doi.org/10.1145/3726302.3729950).
