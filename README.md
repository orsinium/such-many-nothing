# Wow, such many nothing

In February [Kelsey Hightower](https://github.com/kelseyhightower) created [nocode](https://github.com/kelseyhightower/nocode) -- most minimalistic and famous repository without any code. It's have only 3 commits, but also it's have [more than 300 Pull Requests](https://github.com/kelseyhightower/nocode/pulls). Most of this is empty, but some contains... Code. Or no code.

This repository contains most of this Pull Requests, and also open for any your commits too. Feel free to contribute.

Key conceptions:

+ Community driven. Contributors are welcome.
+ Contains configuration files for all popular tools.
+ Also contains some hype things like [deep learning](./deep_learning), [serverless](serverless.yaml), [kubernetes](./k8s.yaml) etc.

## Why do you do this?

All linters, CI services, builders, packaging systems and other tools needs to config file in your project root directory. I want to show it for you.

## How many people do it?

More than 50. Full list in [AUTHORS](./AUTHORS) file. Also you can generate it yourself:

```bash
git clone https://github.com/orsinium/nocode.git
cd nocode
git log --format='%an <%ae>' | sort | uniq
```

## What can I contribute?

Feel free to contribute any minimal configuration files, required for some popular tool like [docker](./Dockerfile), [pip](./requirements.txt), [npm](./package.json) etc.

And also don't trust to [contributing guide](./CONTRIBUTING.md) and other things in this repo. This is moved from nocode repository. I don't change anything in this.
