# introducing-machine
A machine that introduces new concepts and ideas.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Introduce a new concept here, machine." \
  | uvx introducing-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install introducing-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
introducing-machine -a multilogue.txt
```
Or:
```bash
introducing-machine multilogue.txt > response.txt
```
Or:
```bash
introducing-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import introducing_machine
```
