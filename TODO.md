**Open DICOM<em>web</em>**
### TODO In Order

1. Detect Transfer syntax

  - [ ] Add transfer syntax getter to each instance
  - [ ] Error out on implicit little endian
  - [ ] Pretty print a study series on instance
  - [ ] Fix logging so it can be controlled
  - [ ] Fix System one log call

2. De-Identify the Study

  - [ ] Implement Basic Profile
  - [ ] Implement Study Difference tool (byte-for-byte)
  - [ ] Implement SOP de-id, but structured for code reuse
  - [ ] Patient information
       - [ ] remove
       - [ ] prefix with ordering
       - [ ] random value with prefix and suffix
  - [ ] remove private tags
  - [ ] remove curve data   50xx
  - [ ] remove overlay data 60xx


Write large SOP Studies

### Backlog

1. Implement other de-identification options



