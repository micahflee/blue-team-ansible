# Blue Team Ansible

Ansible playbooks for spinning up infrastructure and defending networks in attack/defense CTF.

## Getting Started

I'm using DigitalOcean to deploy new infrastructure. To use these features, you'll need to login to your DigitalOcean account, create an API key, and then make sure it's stored in the `DO_API_KEY` environment variable, like this:

```
export DO_API_KEY=[your_api_key_here]
```

You can run that line to set the environment variable. But, if you want, you can also copy that line into your `~/.bashrc` file so it always gets automatically set. Be careful to protect your API key though. Anyone who has it can create/delete DigitalOcean VPSes in your account.

Install python2 dependencies with pip (you made need to install `python-pip` first):

```
pip install -r requirements.txt
```
