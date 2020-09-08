## Find all files with extension '.spec.ts.off' and rename them to '.spec.ts'

`find ./src/app -name "*.spec.ts.off" | sed -e 's%\.off%%' | xargs -I {} mv {}.off {}`
