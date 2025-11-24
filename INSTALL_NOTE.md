# Installation Note

## Repository Status: Private

The jctl repository is currently **private**, which means Homebrew installation is **not available** at this time.

Homebrew requires release assets to be publicly accessible, which is only possible with a public repository.

### Current Installation Methods

Until the repository is made public, install jctl using pip:

```bash
# Install from PyPI (when published)
pip install jctl

# Or install from source
git clone https://github.com/avidala/jctl.git
cd jctl
pip install -e .
```

### When Will Homebrew Work?

Homebrew installation will work once:
1. The repository is made public, OR
2. The package is published to PyPI and we update the formula to use PyPI URLs

### Making the Repository Public

To enable Homebrew installation:

```bash
gh repo edit avidala/jctl --visibility public
```

After making it public, Homebrew users can install with:

```bash
brew install avidala/jctl/jctl
```

---

The formula is ready and waiting! Just needs the repo to be public.
