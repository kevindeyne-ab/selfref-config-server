# Selfref bug

Works together with https://github.com/kevindeyne-ab/sample-config-repo

## To reproduce:
- Checkout this repo
- mvn spring-boot:run
- Go to http://localhost:8080/works/dev and see the config server works and serves some configuration
- Go to http://localhost:8080/bug/dev and see it load forever
- Go to http://localhost:8080/works/dev and see that this is impacted as well
