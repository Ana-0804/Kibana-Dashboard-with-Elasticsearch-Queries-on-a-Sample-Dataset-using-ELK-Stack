echo "# Kibana Visualizations" > README.md
echo "## How to Import" >> README.md
echo "1. Go to Stack Management > Saved Objects > Import" >> README.md
echo "2. Upload the \`export.ndjson\` file." >> README.md
git add README.md
git commit -m "Added README for importing visualizations"
git push
