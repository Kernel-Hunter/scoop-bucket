# Kernel-Hunter Scoop bucket

[Scoop](https://scoop.sh) manifests for [Mudroom](https://github.com/Kernel-Hunter/mudroom).

```powershell
scoop bucket add kernel-hunter https://github.com/Kernel-Hunter/scoop-bucket
scoop install mudroom
```

Mudroom runs agents in Linux containers, so you also need Docker Desktop (WSL 2 backend) or Podman with a Podman machine. Then build the agent image once:

```powershell
mudroom image build --backend docker
```
