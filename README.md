# kub-train-charts


kubectl port-forward svc/argocd-server -n argocd 8080:443

.\argocd app create kub-train-argo --repo https://github.com/bisento1119/kub-train-charts.git --path Charts/kub-train-app --dest-server https://kubernetes.default.svc --dest-namespace kub-train-dev