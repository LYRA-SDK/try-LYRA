# LYRA AI: Privacy-First Fitness Intelligence

## Why LYRA?  
Fitness studios collect tons of health data but struggle to keep it safe. **A 2024 analysis by Surfshark found that 80% of top fitness apps share user data with third parties**, risking massive GDPR fines and destroying member trust. LYRA fixes this problem with:  
- **Differential Privacy** – We add just enough noise to protect individual identities while keeping insights valuable.  
- **Federated Learning** – Train models across multiple studios without raw data ever leaving their walls.  
- **Actionable Fitness Insights** – Spot injury risks before they happen while keeping member data private.  

---

## Try LYRA 
See our privacy-first approach in action:  
1. **Run the Docker Container**  
   - Build with `docker build -t lyra-mvp .`
   - Launch with `docker run -p 5001:5000 -p 8502:8501 lyra-mvp`
   - Access the dashboard at http://localhost:8502
   
2. **Explore the Demo**
   - Upload our sample_data.csv (or generate your own with sample.py)
   - Watch how member IDs get anonymized automatically
   - See the privacy budget metrics in real-time
   - Get actionable injury risk predictions without compromising privacy

No need to choose between insights and privacy - LYRA delivers both.

## Technical Details

LYRA uses a combination of technologies to ensure privacy while providing valuable insights:

- **API-based Architecture**: Separate frontend and backend services for scalability
- **Docker Containerization**: Easy deployment across environments
- **Streamlit Dashboard**: Intuitive interface for fitness professionals
- **Mathematical Privacy Guarantees**: Epsilon values track privacy budget usage

## For Developers

The repository is structured as follows:

```
lyra-mvp/
├── requirements.txt      # Python dependencies
├── Dockerfile            # Container configuration
└── src/
    ├── streamlit_app.py  # Frontend user interface
    ├── api_server.py     # Backend privacy-preserving API
    ├── sample_data.csv   # Example dataset
    └── data_generator.py # Tool to create synthetic data
```

