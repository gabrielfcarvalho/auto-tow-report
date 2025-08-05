# Tow Report CV Pipeline

End-to-end pipeline for towing incident reports:
- **Plate OCR** → reads Brazilian license plates
- **Damage detection** → YOLO model on CarDD
- **BLIP captioning** → natural language description of damage
- **Report generation** → structured PDF/JSON outputs

Datasets (Kaggle):
- Brazilian Plates for OCR.  
- Blip for Captioning Car Damage.  
- CarDD with YOLO Annotations (images + labels).  
- Tow Report Dataset (final results).  
See **docs/datasets.md** for links.
