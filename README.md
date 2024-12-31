kubectl port-forward svc/el-echo-listener 8080:8080 -n <your namespace>

Can be triggered with:
curl -X POST \
  -H "Content-Type: application/json" \
  -d '{"message": "Hello Tekton!"}' \
  http://localhost:8080

