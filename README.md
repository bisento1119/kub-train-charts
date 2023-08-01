# kub-train-charts

.\argocd app create kub-train-argo --repo https://github.com/bisento1119/kub-train-charts.git --path Charts/kub-train-app --dest-server https://kubernetes.default.svc --dest-namespace kub-train-dev