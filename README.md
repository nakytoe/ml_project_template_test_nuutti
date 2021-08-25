# Your project name
> One-sentence description of your project.


```
%load_ext lab_black
# nb_black if running in jupyter
```

## About

Describe your project in a general level. What problem does it solve?

## Contents

Briefly describe the contents of your repository

## How to Install

Describe how to install your code. Be very through and include every single step of the process.

## How to Use / API

Describe how to use your code. Give code examples.

## Update Plan

How is your model and data kept up to date?

## Ethical Aspects

Can you recognize ethical issues with your ML project?

Is there a risk for bias, discrimination, violation of privacy or conflict with the local or global laws?

Could your results or algorithms be misused for malicious acts?

Can data or model updates include bias in your model? 

How have you tackled these issues in your implementation?

## Contributing
{% include note.html content='Edit the hyperlink below to point to the CONTRIBUTING.md file of your repository' %}
See [here](https://github.com/City-of-Helsinki/ml_project_template/blob/master/CONTRIBUTING.md) on how to contribute to this project.


## How to Cite this Work (optional)

If you are doing a research project, you can add bibtex and other citation templates here.
You can also get a doi for your code by adding it to a code archive,
so your code can be cited directly!

To cite this work, use:

    @misc{authoryearfirstwordinheader,
    title = ...
    ...
    }

## Copyright
{% include note.html content='Edit the year and author below according to your project!' %}
Copyright 2021 City-of-Helsinki. Licensed under the Apache License, Version 2.0 (the "License");
you may not use this project's files except in compliance with the License.
A copy of the License is provided in the LICENSE file in this repository.
{% include note.html content='If you are using this template for other than city of Helsinki projects, remove the Helsinki logo files `favicon.ico` and `company_logo.png` from `docs/assets/images/`.' %}
    # to remove remove helsinki logo and favicon:
    git rm docs/assets/images/favicon.ico docs/assets/images/company_logo.png
    git commit -m "removed Helsinki logo and favicon"

The Helsinki logo is a registered trademark, and may only be used by the city of Helsinki.

This project was built using [nbdev](https://nbdev.fast.ai/) on top of the city of Helsinki [ml_project_template](https://github.com/City-of-Helsinki/ml_project_template).
