# trip

trip is a cli tool written in typescript for scraping erowid experience vaults

## usage

```bash
trip [command] [options]
```

### commands

#### scrape

scrape erowid experience vaults

```bash

trip scrape [options]

```

##### options

```
  [drug name]
```

scrape for a specific drug

**the default setting** is to scrape for the drug alone, not including experiences with other drugs.

```
 -i [drug name]
```

scrape for a specific drug including experiences with other drugs

```
  --list, -l
```

scrape for a list of all drugs

page [page number] scrape a specific page
refresh [list name] refresh a list

```

#### word
```
