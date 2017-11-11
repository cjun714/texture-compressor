# Texture compressor

Tool for texture compression using ASTC, ETC, PVR and S3TC in a DSS container

## Status

	Work in progress

## Example

	General:
	-i, --input ./example/example.png
	-o, --output ./example/example.dds
	-m, --method s3tc
	-c, --compression dxt5

	Optional:
	-f, --flags "mipmode none" "quality 100"

    node ./bin/texture-compressor.js -i ./example/example.png -o ./example/example-dxt5.dds -m s3tc -c dxt5 -f "mipmode none" "quality 100"
