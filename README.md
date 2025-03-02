## Why LYRA?  
Fitness studios collect tons of health data but struggle to keep it safe. **60% of fitness apps leak sensitive information** (FTC 2024), risking massive GDPR fines and destroying member trust. LYRA fixes this problem with:  
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

