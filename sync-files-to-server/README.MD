### Simple playbook to sync files
#### Type your hosts inside:
`- hosts: [YOUR_HOSTS]`

#### Choose the source and destination:

`src: [SOURCE_DIRECTORY]
dest: [DESTINATION_DIRECTORY]`

#### Run command:
`ansible-playbook -K sync.yml`
