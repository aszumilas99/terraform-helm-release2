# Usage
### Please add the following code
```
module "app" {
  source    = "aszumilas99/release2/helm"
  namespace = "default"
  name      = "wordpress"
  wait      = false
  chart     = "./application"
  values = []
}
```
