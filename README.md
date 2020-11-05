# gcp-cloud-functions
quick demo

### Gotchas

Make sure you auth your cloud shell:  `gcloud auth list`

### Example payload from CLI

```
gcloud functions call translate-wikipedia --data '{"entity":"facebook", "sentences": "20", "langu
age":"es"}'

```

### Screenshot

![Screen Shot 2020-11-04 at 8 30 56 PM](https://user-images.githubusercontent.com/58792/98186408-ae3ffe80-1edc-11eb-92fd-cbb9a58f9431.png)
