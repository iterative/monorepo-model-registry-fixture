This is a [DVC Studio](https://studio.iterative.ai) testing (fixture) repository.

## `<root>/` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='true'
OPT_MODEL_NAME='text-classification'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='true'
OPT_SUBDIR=''
OPT_TAGS='false'
OPT_TAG_MODELS='false'
OPT_TESTING_REPO='true'
```

## `<root>/nested` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='text-classification'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='true'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='false'
OPT_SUBDIR='nested'
OPT_TAGS='false'
OPT_TAG_MODELS='true'
OPT_TESTING_REPO='true'
```

## `<root>/nested/dvc-subdir-same-model` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='text-classification'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='true'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='true'
OPT_SUBDIR='nested/dvc-subdir-same-model'
OPT_TAGS='false'
OPT_TAG_MODELS='false'
OPT_TESTING_REPO='true'
```

## `<root>/nested/slice-same-model` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='false'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='text-classification'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='true'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='false'
OPT_SUBDIR='nested/slice-same-model'
OPT_TAGS='false'
OPT_TAG_MODELS='true'
OPT_TESTING_REPO='true'
```

## `<root>/nested/dvc-subdir-new-model` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='new-model'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='true'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='false'
OPT_SUBDIR='nested/dvc-subdir-new-model'
OPT_TAGS='false'
OPT_TAG_MODELS='true'
OPT_TESTING_REPO='true'
```

## `<root>/nested/slice-new-model` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='false'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='new-model'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='true'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='true'
OPT_SUBDIR='nested/slice-new-model'
OPT_TAGS='false'
OPT_TAG_MODELS='false'
OPT_TESTING_REPO='true'
```

## `<root>/nested/dvc-subdir-no-models` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='new-model'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-s3'
OPT_SQUASH_COMMITS='true'
OPT_SUBDIR='nested/dvc-subdir-no-models'
OPT_TAGS='false'
OPT_TAG_MODELS='false'
OPT_TESTING_REPO='true'
```

## `<root>/nested/slice-no-models` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='false'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='new-model'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-ssh'
OPT_SQUASH_COMMITS='true'
OPT_SUBDIR='nested/slice-no-models'
OPT_TAGS='false'
OPT_TAG_MODELS='false'
OPT_TESTING_REPO='true'
```
