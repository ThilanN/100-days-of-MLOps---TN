# Fix a Broken uv Lockfile Specification

Fix the `requirements.in` file and generate a pinned `requirements.txt` using `uv`.

---

## Steps

### 1. VS Code (easy way)

Open the project in VS Code → Explorer → open `requirements.in`.

Replace everything with:

```text
scikit-learn
mlflow
pandas
numpy
```


---

### Command Line (alternative way)

```bash
ls
cd fraud-detection
ls
vi requirements.in
```

Remove everything and add:

```text
scikit-learn
mlflow
pandas
numpy
```

Save and exit.

---

### 2. Compile

type and Run in the terminal:

```bash
uv pip compile requirements.in -o requirements.txt
```

---

### 4. Check output

```bash
cat requirements.txt 
```

Make sure:

* all 4 packages are there
* versions are pinned with `==`
* transitive dependencies are included automatically

---

Done.
