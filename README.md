# This example uses conda environments within rules 

aka requires use of `--use-conda` flag

```json
{
  "conda_env_file_path": "workflow/envs/pipeline_env.yaml",
  "config_file_path": "workflow/config/config.yaml",
  "git_url": "",
  "output_files": [
    "results/output.txt"
  ],
  "pipeline_name": "snakemake_bioconductor",
  "snakefile_path": "workflow/Snakefile"
}
```