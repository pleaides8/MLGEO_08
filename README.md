# MLGEO_08

I'm pleaides8 and I want to create a Geotechnical ML project

## How to run

1. Install pixi running the following commands. 
Pixi works for Linux systems, reccomending WSL for Windows.

```sh
curl -fsSL https://pixi.sh/install.sh | sh   # or: brew install pixi
pixi --version                               # restart the terminal if not found
```

2. Clone this repository into your machine at the desired location
```
git clone https://github.com/pleaides8/MLGEO_08
cd MLGEO_08
```
Make sure that the pixi.lock and pixi.toml files are present in your repository.
Then install the required libraries

```pixi install```

3. Run a smoke test to make sure that everthing works fine

``` pixi run smoke ```

If the result is "smoke test passed" then the environment is initialized. For reference, the smoke test was tested on Linux x86_64.
