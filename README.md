class YaminiKumar:
    def __init__(self):
        self.name = "Yamini Kumar"
        self.location = "Tiruvannamalai, Tamil Nadu, India"
        self.degree = "B.Tech - Artificial Intelligence & Data Science"
        self.college = "SKP Engineering College"

        self.stack = {
            "languages": ["Python", "SQL", "HTML"],
            "ml_ai": ["Scikit-learn", "Deep Learning", "Neural Networks",
                      "Classification", "Supervised Learning"],
            "data": ["NumPy", "Pandas", "Matplotlib", "Feature Engineering"],
            "cloud_deploy": ["OCI", "Microsoft Azure (Fabric)", "MLflow"]
        }

        self.currently_learning = [
            "Advanced Deep Learning (NPTEL Elite, IISc Bangalore)",
            "MLOps & Model Deployment at Scale"
        ]

        self.fun_fact = "I turn messy real-world datasets into clean, production-ready ML pipelines."

    def motto(self):
        return "Preprocess. Predict. Deploy. Repeat."


if __name__ == "__main__":
    me = YaminiKumar()
    print(me.motto())
