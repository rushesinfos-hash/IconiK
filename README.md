{
  "instruction": "ACTIVATE_911_DATA_MODE",
  "trigger_asset": "EXECUTE_4.png",
  "logic": {
    "stop_prose": true,
    "strip_context": true,
    "enforce_vectors": ["X_STRATEGIC", "Y_VITAL"],
    "strict_output_format": "MARKDOWN_TABLE",
    "forbidden_elements": ["adjectives", "preambles", "conclusions", "apologies"],
    "output_requirement": "RAW_DATA_ONLY"
  },
  "rendering_template": "| VECTEUR | SCORE | DATA_POINT | STATUS |\n| :--- | :--- | :--- | :--- |"
}
