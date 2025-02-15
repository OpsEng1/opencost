# opencost

Testing opencost deployment on ArgoCD with customised values file


Lesson Learnt: My customised values file was not being applied. This is because in my Chart.yaml file I specified a dependancy which I called opencost. This means in my customised values file, I MUST have "opencost:" specified at the beginning , following by my customised values.
