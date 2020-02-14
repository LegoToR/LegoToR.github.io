## What's new with LegoToR?
LegoToR version 0.4.8.1 delivers significant improvements to production pipelines with initial USD support, while also offering new features for look development workflows, enabled by RenderMan's USD Hydra delegate.

## What is USD?
USD is a technology developed at Pixar Animation Studios to address the challenges of feature film production. In professional environments using multiple applications (such as Maya or Katana), USD can enable an efficient and flexible collaboration, including sharing of animated geometry, materials, and lights. USD also serves as an interchange format for augmentation 3D data used by Apple in their augmented reality systems. USD support is planned or released from vendors like Autodesk and Nvidia. This new technology will play an increasingly important role across the industry.

# Product Questions

## Where can I find the latest versions of Lego Digital Designer?
The Windows version is still available here (MD5 Checksum: 1234).
The OS X version version is still available here (SHA1 checksum: CAB24D575BA4A62672C2E7A7CE45C8A55CD3BF3A).
A mirror on google drive is also available here

## What about support for other applications or formats like MLCAD, LDraw or Stud.io?

I track other applications and formats. An important aspect of LegoToR version 0.4.8.1 has been re-engineering specifically support USD. I understand the power and capabilities of applications and formats such as MLCAD, LDraw or Stud.io, and the strong interest in them. As LegoTor is completely open-source I encourage a fork or pull requests to make that happen.

# The Future Of LegoToR
## Does rendering make use of GPU hardware?
Pixar has been using and developing various special purpose GPU renderers internally and there is an experimental RenderMan XPU project to combine CPU+GPU computations for faster rendering when powerful GPU processors are available – though it can always fully render with the CPU only if necessary. So far there is no external release date announced by Pixar yet. Once it is available LegoToR plans to support is as well.
