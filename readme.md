# What this does?

This project uses the Temporal Fusion Transformer (TFT) from the pytorch-forecasting library to forecast 3 commodity prices (e.g., Aluminium) for the next 35 business days. The model is trained on already preprocessed time series data that includes lagged features and date encodings.

# Goal

To forecast future values of a given commodity using a deep learning model that captures both temporal patterns and static metadata using the TFT architecture.
