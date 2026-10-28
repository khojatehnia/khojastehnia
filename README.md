









------------------------
          # e.g. "torvalds"
           x"
         

XXXXXXXXXXXXXXXXXXXXXXXXXXXX"

 

(quickest way o et thole repo)
# ----------------------------
= ://pi.gcom/reponer}/{ro}/zipball/{branch}"
headers)


# ack the zip into a local folder
zip_bytes = io.BytesIO(resp.content)
wi zipfile.ZipFile(zip_bytes) as z:
    # The zip contains a top‑level folder like "owner-repo-<hash>"
    # Extract everything into a folder named after the repo
    extract_path = f"./{repo}"
    os.makedirs(extract_path, exist_ok=True)
    extractall(path=extract_path)

print(f"✅  Repository '{owner}/{repo}' extracted to ./{repo}")


