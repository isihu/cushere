# cushere
Cushere stands for **Cus**tom **he**lm **re**sources
 and is a controller that you can register Helm charts with.
The controller will then create a Custom Resource for you based on the charts `values.schema.json` and will take care of applying the helm chart for each time someone applies the Custom resources.
It is basically a server-side helm renderer with the difference that you offer a custom resource for each helm chart.


Offer Helm charts as Kubernetes custom resources without writing code
