✅ Advantages

Learns without labels (unsupervised).

Can extract useful features from raw data.

Useful in real-time anomaly detection and noise removal.

Helps visualize complex data in a lower-dimensional space.

---

| Limitation                      | Description                                                                  |
| ------------------------------- | ---------------------------------------------------------------------------- |
| ❌ **Blurry Reconstructions**    | Outputs are often smooth and lack sharp details, especially in image tasks.  |
| ❌ **Unstructured Latent Space** | Basic autoencoders don’t guarantee useful or interpretable latent variables. |
| ❌ **Poor for Image Generation** | Generated samples from the latent space are low quality compared to GANs.    |
| ❌ **Overfitting Risk**          | If the latent space is too large, the model may simply copy the input.       |
| ❌ **Sensitive Bottleneck Size** | Too small → loss of detail; too large → no compression benefit.              |
| ❌ **Limited Disentanglement**   | Latent space may mix unrelated features (e.g., shape & color together).      |
