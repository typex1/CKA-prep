# CKA-prep
CKA (Certified Kubernetes Administrator) prep contents

* Official CNCF link: https://www.cncf.io/training/certification/cka/
* Youtube Video "CKA Exam Tips: How To Crack The Exam In 2023 | Certified Kubernetes Administrator | KodeKloud" https://www.youtube.com/watch?v=8LJibrSurKA
* Youtube Video "How to Pass the CKA Exam on Your First Attempt | 2023 Guide" https://www.youtube.com/watch?v=YMxHK7FRlV0

bashrc entries mentioned in the above video:
```
alias k="kubectl"
alias v="vim"

function ns () {
  kubectl config set-context --current --namespace=$1
}

export drc="--dry-run=client -oyaml"
export drs="--dry-run=server -oyaml"
```
