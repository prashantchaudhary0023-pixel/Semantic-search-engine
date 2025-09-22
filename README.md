# Semantic-search-engine
Semantic search on csv files using all-MiniLM-L6-v2. No LLMs involved — retrieves contextually relevant results through embedding-based similarity, ideal for efficient, resource-friendly information retrieval.


install these libraries and import
import pandas as pd
from pinecone import Pinecone,ServerlessSpec
from tqdm import tqdm
from sentence_transformers import SentenceTransformer
import torch
