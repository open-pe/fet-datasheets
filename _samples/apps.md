## pix2text
```
p2t predict -l en --resized-shape 2048 --file-type pdf \
    -i input.pdf -o output.md
    
p2t predict -l en --resized-shape 2048 --file-type pdf \
    -i datasheets/_samples/BSC070N10NS3GATMA1_crop.pdf -o output-md \
    --save-debug-res output-debug-p2t 
    
    --mfd-config '{"model_name": "mfd-pro", "model_backend": "onnx"}' 
    --formula-ocr-config '{"model_name":"mfr-pro","model_backend":"onnx"}' 
    --text-ocr-config '{"rec_model_name": "doc-densenet_lite_666-gru_large"}'

```

## ocrmypdf


## pdfplumber
```
pdfplumber < datasheets/vishay/SIR680ADP-T1-RE3.pdf
 
```

## Tabula


## pix2image


