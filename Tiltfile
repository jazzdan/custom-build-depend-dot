k8s_yaml('config.yaml')

custom_build(
  'test',
  'docker build -t $EXPECTED_REF .',
  ['.'],
)