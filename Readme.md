helm upgrade --install victoria1 --namespace victoria1 . --atomic
helm upgrade --install victoria2 --namespace victoria2 . --atomic
helm upgrade --install -n prom . --atomic --wait
