View [schema.md](schema.md) or [schema.minerva.hoff.in](http://schema.minerva.hoff.in/)

### Usage

HTML
```bash
generate-schema-doc --config-file schema_doc.yaml schema docs/index.html
cp schema_doc.css docs/schema_doc.css
```

MD
```bash
generate-schema-doc --config-file schema_md.yaml schema schema.md
vi schema.md "+%s@.*\*\*Additional properties\*\*.*\n@@g" "+:wq"
```
