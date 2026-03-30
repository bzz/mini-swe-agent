# Litellm Model

!!! note "LiteLLM Model class"

    - [Read on GitHub](https://github.com/swe-agent/mini-swe-agent/blob/main/src/minisweagent/models/litellm_model.py)

    ??? note "Full source code"

        ```python
        --8<-- "src/minisweagent/models/litellm_model.py"
        ```

!!! tip "Guides"

    * Setting up most models is covered in the [quickstart guide](../../quickstart.md).
    * If you want to use local models, please check this [guide](../../models/local_models.md).
    * For Tinker models via LiteLLM, install optional deps with `mini-swe-agent[tinker]` and use a `tinker/...` model name with `model_kwargs.base_model` (see [model setup quickstart](../../models/quickstart.md)).

::: minisweagent.models.litellm_model

{% include-markdown "../../_footer.md" %}
