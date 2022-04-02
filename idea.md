Quickstart
```
openai.api_key = "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"

openai.Classification.create(
  search_model="ada",
  model="curie",
  examples=[
    ["I ate a chocolate bar.", "food"],
    ["Buy one bar.", "food"],
    ["This is my favourite bar.", "establishment"],
["Make me a snack with those bars.", "food"]
  ],
  query="Let's go to a bar.",
  labels=["food", "est	¸-*+a
blishment"],
)
```
