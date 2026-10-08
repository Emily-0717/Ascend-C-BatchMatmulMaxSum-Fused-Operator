# Ascend-C-BatchMatmulMaxSum-Fused-Operator
Ascend C fused BatchMatmulMaxSum operator for CANN 9.0 and ColBERT/RAG reranking. Combines batched matmul, MaxSim, and sum in one kernel launch. Supports FP16/BF16 inputs, FP32 accumulation, four storage layouts, and unaligned dimensions. NPU validation is ongoing.
