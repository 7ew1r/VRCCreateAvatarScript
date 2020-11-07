# vrc-create-avatar-script

テンプレートからアバター作成用のプロジェクトファイルを生成するスクリプト

## Requirement

- `powershell`
- `git`

## Usage

**1. 作業用ディレクトリに移動する。**

`mkdir repos; cd repos`

**2. `createNewAvatar.ps1` を配置する。**

**3. テンプレートとなるプロジェクトを以下の名前で作成する。**

- `_Template_VRC-Avatar`
- `_Template_VRC-Avatar-3.0`

VRCSDK と Dynamic Bone や各種拡張機能などをインポートしておく。

**4. スクリプトを実行する。**

`./createNewAvatar.ps1`

`VRC-Avatar_AvatarName` といった名前のプロジェクトが生成される。
