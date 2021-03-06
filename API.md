# API Reference <a name="API Reference"></a>

## Constructs <a name="Constructs"></a>

### ArchiveProvider <a name="@cdktf/provider-archive.ArchiveProvider"></a>

Represents a {@link https://www.terraform.io/docs/providers/archive archive}.

#### Initializers <a name="@cdktf/provider-archive.ArchiveProvider.Initializer"></a>

```typescript
import { ArchiveProvider } from '@cdktf/provider-archive'

new ArchiveProvider(scope: Construct, id: string, config?: ArchiveProviderConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-archive.ArchiveProvider.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-archive.ArchiveProvider.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="@cdktf/provider-archive.ArchiveProvider.parameter.config"></a>

- *Type:* [`@cdktf/provider-archive.ArchiveProviderConfig`](#@cdktf/provider-archive.ArchiveProviderConfig)

---

#### Methods <a name="Methods"></a>

##### `resetAlias` <a name="@cdktf/provider-archive.ArchiveProvider.resetAlias"></a>

```typescript
public resetAlias()
```


#### Properties <a name="Properties"></a>

##### `aliasInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.ArchiveProvider.property.aliasInput"></a>

```typescript
public readonly aliasInput: string;
```

- *Type:* `string`

---

##### `alias`<sup>Optional</sup> <a name="@cdktf/provider-archive.ArchiveProvider.property.alias"></a>

```typescript
public readonly alias: string;
```

- *Type:* `string`

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-archive.ArchiveProvider.property.tfResourceType"></a>

- *Type:* `string`

---

### DataArchiveFile <a name="@cdktf/provider-archive.DataArchiveFile"></a>

Represents a {@link https://www.terraform.io/docs/providers/archive/d/file archive_file}.

#### Initializers <a name="@cdktf/provider-archive.DataArchiveFile.Initializer"></a>

```typescript
import { DataArchiveFile } from '@cdktf/provider-archive'

new DataArchiveFile(scope: Construct, id: string, config: DataArchiveFileConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.parameter.config"></a>

- *Type:* [`@cdktf/provider-archive.DataArchiveFileConfig`](#@cdktf/provider-archive.DataArchiveFileConfig)

---

#### Methods <a name="Methods"></a>

##### `putSource` <a name="@cdktf/provider-archive.DataArchiveFile.putSource"></a>

```typescript
public putSource(value: IResolvable | DataArchiveFileSource[])
```

###### `value`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.parameter.value"></a>

- *Type:* [`cdktf.IResolvable`](#cdktf.IResolvable) | [`@cdktf/provider-archive.DataArchiveFileSource`](#@cdktf/provider-archive.DataArchiveFileSource)[]

---

##### `resetExcludes` <a name="@cdktf/provider-archive.DataArchiveFile.resetExcludes"></a>

```typescript
public resetExcludes()
```

##### `resetId` <a name="@cdktf/provider-archive.DataArchiveFile.resetId"></a>

```typescript
public resetId()
```

##### `resetOutputFileMode` <a name="@cdktf/provider-archive.DataArchiveFile.resetOutputFileMode"></a>

```typescript
public resetOutputFileMode()
```

##### `resetSource` <a name="@cdktf/provider-archive.DataArchiveFile.resetSource"></a>

```typescript
public resetSource()
```

##### `resetSourceContent` <a name="@cdktf/provider-archive.DataArchiveFile.resetSourceContent"></a>

```typescript
public resetSourceContent()
```

##### `resetSourceContentFilename` <a name="@cdktf/provider-archive.DataArchiveFile.resetSourceContentFilename"></a>

```typescript
public resetSourceContentFilename()
```

##### `resetSourceDir` <a name="@cdktf/provider-archive.DataArchiveFile.resetSourceDir"></a>

```typescript
public resetSourceDir()
```

##### `resetSourceFile` <a name="@cdktf/provider-archive.DataArchiveFile.resetSourceFile"></a>

```typescript
public resetSourceFile()
```


#### Properties <a name="Properties"></a>

##### `outputBase64Sha256`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputBase64Sha256"></a>

```typescript
public readonly outputBase64Sha256: string;
```

- *Type:* `string`

---

##### `outputMd5`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputMd5"></a>

```typescript
public readonly outputMd5: string;
```

- *Type:* `string`

---

##### `outputSha`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputSha"></a>

```typescript
public readonly outputSha: string;
```

- *Type:* `string`

---

##### `outputSize`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputSize"></a>

```typescript
public readonly outputSize: number;
```

- *Type:* `number`

---

##### `source`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.source"></a>

```typescript
public readonly source: DataArchiveFileSourceList;
```

- *Type:* [`@cdktf/provider-archive.DataArchiveFileSourceList`](#@cdktf/provider-archive.DataArchiveFileSourceList)

---

##### `excludesInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.excludesInput"></a>

```typescript
public readonly excludesInput: string[];
```

- *Type:* `string`[]

---

##### `idInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* `string`

---

##### `outputFileModeInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputFileModeInput"></a>

```typescript
public readonly outputFileModeInput: string;
```

- *Type:* `string`

---

##### `outputPathInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputPathInput"></a>

```typescript
public readonly outputPathInput: string;
```

- *Type:* `string`

---

##### `sourceContentFilenameInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceContentFilenameInput"></a>

```typescript
public readonly sourceContentFilenameInput: string;
```

- *Type:* `string`

---

##### `sourceContentInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceContentInput"></a>

```typescript
public readonly sourceContentInput: string;
```

- *Type:* `string`

---

##### `sourceDirInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceDirInput"></a>

```typescript
public readonly sourceDirInput: string;
```

- *Type:* `string`

---

##### `sourceFileInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceFileInput"></a>

```typescript
public readonly sourceFileInput: string;
```

- *Type:* `string`

---

##### `sourceInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceInput"></a>

```typescript
public readonly sourceInput: IResolvable | DataArchiveFileSource[];
```

- *Type:* [`cdktf.IResolvable`](#cdktf.IResolvable) | [`@cdktf/provider-archive.DataArchiveFileSource`](#@cdktf/provider-archive.DataArchiveFileSource)[]

---

##### `typeInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* `string`

---

##### `excludes`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.excludes"></a>

```typescript
public readonly excludes: string[];
```

- *Type:* `string`[]

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `outputFileMode`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputFileMode"></a>

```typescript
public readonly outputFileMode: string;
```

- *Type:* `string`

---

##### `outputPath`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.outputPath"></a>

```typescript
public readonly outputPath: string;
```

- *Type:* `string`

---

##### `sourceContent`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceContent"></a>

```typescript
public readonly sourceContent: string;
```

- *Type:* `string`

---

##### `sourceContentFilename`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceContentFilename"></a>

```typescript
public readonly sourceContentFilename: string;
```

- *Type:* `string`

---

##### `sourceDir`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceDir"></a>

```typescript
public readonly sourceDir: string;
```

- *Type:* `string`

---

##### `sourceFile`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.sourceFile"></a>

```typescript
public readonly sourceFile: string;
```

- *Type:* `string`

---

##### `type`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFile.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* `string`

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-archive.DataArchiveFile.property.tfResourceType"></a>

- *Type:* `string`

---

### File <a name="@cdktf/provider-archive.File"></a>

Represents a {@link https://www.terraform.io/docs/providers/archive/r/file archive_file}.

#### Initializers <a name="@cdktf/provider-archive.File.Initializer"></a>

```typescript
import { File } from '@cdktf/provider-archive'

new File(scope: Construct, id: string, config: FileConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-archive.File.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-archive.File.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-archive.File.parameter.config"></a>

- *Type:* [`@cdktf/provider-archive.FileConfig`](#@cdktf/provider-archive.FileConfig)

---

#### Methods <a name="Methods"></a>

##### `putSource` <a name="@cdktf/provider-archive.File.putSource"></a>

```typescript
public putSource(value: FileSource[] | IResolvable)
```

###### `value`<sup>Required</sup> <a name="@cdktf/provider-archive.File.parameter.value"></a>

- *Type:* [`@cdktf/provider-archive.FileSource`](#@cdktf/provider-archive.FileSource)[] | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `resetExcludes` <a name="@cdktf/provider-archive.File.resetExcludes"></a>

```typescript
public resetExcludes()
```

##### `resetId` <a name="@cdktf/provider-archive.File.resetId"></a>

```typescript
public resetId()
```

##### `resetOutputFileMode` <a name="@cdktf/provider-archive.File.resetOutputFileMode"></a>

```typescript
public resetOutputFileMode()
```

##### `resetSource` <a name="@cdktf/provider-archive.File.resetSource"></a>

```typescript
public resetSource()
```

##### `resetSourceContent` <a name="@cdktf/provider-archive.File.resetSourceContent"></a>

```typescript
public resetSourceContent()
```

##### `resetSourceContentFilename` <a name="@cdktf/provider-archive.File.resetSourceContentFilename"></a>

```typescript
public resetSourceContentFilename()
```

##### `resetSourceDir` <a name="@cdktf/provider-archive.File.resetSourceDir"></a>

```typescript
public resetSourceDir()
```

##### `resetSourceFile` <a name="@cdktf/provider-archive.File.resetSourceFile"></a>

```typescript
public resetSourceFile()
```


#### Properties <a name="Properties"></a>

##### `outputBase64Sha256`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.outputBase64Sha256"></a>

```typescript
public readonly outputBase64Sha256: string;
```

- *Type:* `string`

---

##### `outputMd5`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.outputMd5"></a>

```typescript
public readonly outputMd5: string;
```

- *Type:* `string`

---

##### `outputSha`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.outputSha"></a>

```typescript
public readonly outputSha: string;
```

- *Type:* `string`

---

##### `outputSize`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.outputSize"></a>

```typescript
public readonly outputSize: number;
```

- *Type:* `number`

---

##### `source`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.source"></a>

```typescript
public readonly source: FileSourceList;
```

- *Type:* [`@cdktf/provider-archive.FileSourceList`](#@cdktf/provider-archive.FileSourceList)

---

##### `excludesInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.excludesInput"></a>

```typescript
public readonly excludesInput: string[];
```

- *Type:* `string`[]

---

##### `idInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* `string`

---

##### `outputFileModeInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.outputFileModeInput"></a>

```typescript
public readonly outputFileModeInput: string;
```

- *Type:* `string`

---

##### `outputPathInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.outputPathInput"></a>

```typescript
public readonly outputPathInput: string;
```

- *Type:* `string`

---

##### `sourceContentFilenameInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.sourceContentFilenameInput"></a>

```typescript
public readonly sourceContentFilenameInput: string;
```

- *Type:* `string`

---

##### `sourceContentInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.sourceContentInput"></a>

```typescript
public readonly sourceContentInput: string;
```

- *Type:* `string`

---

##### `sourceDirInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.sourceDirInput"></a>

```typescript
public readonly sourceDirInput: string;
```

- *Type:* `string`

---

##### `sourceFileInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.sourceFileInput"></a>

```typescript
public readonly sourceFileInput: string;
```

- *Type:* `string`

---

##### `sourceInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.sourceInput"></a>

```typescript
public readonly sourceInput: FileSource[] | IResolvable;
```

- *Type:* [`@cdktf/provider-archive.FileSource`](#@cdktf/provider-archive.FileSource)[] | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `typeInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.File.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* `string`

---

##### `excludes`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.excludes"></a>

```typescript
public readonly excludes: string[];
```

- *Type:* `string`[]

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `outputFileMode`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.outputFileMode"></a>

```typescript
public readonly outputFileMode: string;
```

- *Type:* `string`

---

##### `outputPath`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.outputPath"></a>

```typescript
public readonly outputPath: string;
```

- *Type:* `string`

---

##### `sourceContent`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.sourceContent"></a>

```typescript
public readonly sourceContent: string;
```

- *Type:* `string`

---

##### `sourceContentFilename`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.sourceContentFilename"></a>

```typescript
public readonly sourceContentFilename: string;
```

- *Type:* `string`

---

##### `sourceDir`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.sourceDir"></a>

```typescript
public readonly sourceDir: string;
```

- *Type:* `string`

---

##### `sourceFile`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.sourceFile"></a>

```typescript
public readonly sourceFile: string;
```

- *Type:* `string`

---

##### `type`<sup>Required</sup> <a name="@cdktf/provider-archive.File.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* `string`

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-archive.File.property.tfResourceType"></a>

- *Type:* `string`

---

## Structs <a name="Structs"></a>

### ArchiveProviderConfig <a name="@cdktf/provider-archive.ArchiveProviderConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { ArchiveProviderConfig } from '@cdktf/provider-archive'

const archiveProviderConfig: ArchiveProviderConfig = { ... }
```

##### `alias`<sup>Optional</sup> <a name="@cdktf/provider-archive.ArchiveProviderConfig.property.alias"></a>

```typescript
public readonly alias: string;
```

- *Type:* `string`

Alias name.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive#alias ArchiveProvider#alias}

---

### DataArchiveFileConfig <a name="@cdktf/provider-archive.DataArchiveFileConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { DataArchiveFileConfig } from '@cdktf/provider-archive'

const dataArchiveFileConfig: DataArchiveFileConfig = { ... }
```

##### `connection`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.connection"></a>

```typescript
public readonly connection: ISSHProvisionerConnection | IWinrmProvisionerConnection;
```

- *Type:* [`cdktf.ISSHProvisionerConnection`](#cdktf.ISSHProvisionerConnection) | [`cdktf.IWinrmProvisionerConnection`](#cdktf.IWinrmProvisionerConnection)

---

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.count"></a>

```typescript
public readonly count: number;
```

- *Type:* `number`

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `forEach`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* [`cdktf.ITerraformIterator`](#cdktf.ITerraformIterator)

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `provisioners`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.provisioners"></a>

```typescript
public readonly provisioners: IFileProvisioner | ILocalExecProvisioner | IRemoteExecProvisioner[];
```

- *Type:* [`cdktf.IFileProvisioner`](#cdktf.IFileProvisioner) | [`cdktf.ILocalExecProvisioner`](#cdktf.ILocalExecProvisioner) | [`cdktf.IRemoteExecProvisioner`](#cdktf.IRemoteExecProvisioner)[]

---

##### `outputPath`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.outputPath"></a>

```typescript
public readonly outputPath: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#output_path DataArchiveFile#output_path}.

---

##### `type`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#type DataArchiveFile#type}.

---

##### `excludes`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.excludes"></a>

```typescript
public readonly excludes: string[];
```

- *Type:* `string`[]

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#excludes DataArchiveFile#excludes}.

---

##### `id`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#id DataArchiveFile#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `outputFileMode`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.outputFileMode"></a>

```typescript
public readonly outputFileMode: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#output_file_mode DataArchiveFile#output_file_mode}.

---

##### `source`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.source"></a>

```typescript
public readonly source: IResolvable | DataArchiveFileSource[];
```

- *Type:* [`cdktf.IResolvable`](#cdktf.IResolvable) | [`@cdktf/provider-archive.DataArchiveFileSource`](#@cdktf/provider-archive.DataArchiveFileSource)[]

source block.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#source DataArchiveFile#source}

---

##### `sourceContent`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.sourceContent"></a>

```typescript
public readonly sourceContent: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#source_content DataArchiveFile#source_content}.

---

##### `sourceContentFilename`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.sourceContentFilename"></a>

```typescript
public readonly sourceContentFilename: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#source_content_filename DataArchiveFile#source_content_filename}.

---

##### `sourceDir`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.sourceDir"></a>

```typescript
public readonly sourceDir: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#source_dir DataArchiveFile#source_dir}.

---

##### `sourceFile`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileConfig.property.sourceFile"></a>

```typescript
public readonly sourceFile: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#source_file DataArchiveFile#source_file}.

---

### DataArchiveFileSource <a name="@cdktf/provider-archive.DataArchiveFileSource"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { DataArchiveFileSource } from '@cdktf/provider-archive'

const dataArchiveFileSource: DataArchiveFileSource = { ... }
```

##### `content`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSource.property.content"></a>

```typescript
public readonly content: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#content DataArchiveFile#content}.

---

##### `filename`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSource.property.filename"></a>

```typescript
public readonly filename: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/d/file#filename DataArchiveFile#filename}.

---

### FileConfig <a name="@cdktf/provider-archive.FileConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { FileConfig } from '@cdktf/provider-archive'

const fileConfig: FileConfig = { ... }
```

##### `connection`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.connection"></a>

```typescript
public readonly connection: ISSHProvisionerConnection | IWinrmProvisionerConnection;
```

- *Type:* [`cdktf.ISSHProvisionerConnection`](#cdktf.ISSHProvisionerConnection) | [`cdktf.IWinrmProvisionerConnection`](#cdktf.IWinrmProvisionerConnection)

---

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.count"></a>

```typescript
public readonly count: number;
```

- *Type:* `number`

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `forEach`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* [`cdktf.ITerraformIterator`](#cdktf.ITerraformIterator)

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `provisioners`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.provisioners"></a>

```typescript
public readonly provisioners: IFileProvisioner | ILocalExecProvisioner | IRemoteExecProvisioner[];
```

- *Type:* [`cdktf.IFileProvisioner`](#cdktf.IFileProvisioner) | [`cdktf.ILocalExecProvisioner`](#cdktf.ILocalExecProvisioner) | [`cdktf.IRemoteExecProvisioner`](#cdktf.IRemoteExecProvisioner)[]

---

##### `outputPath`<sup>Required</sup> <a name="@cdktf/provider-archive.FileConfig.property.outputPath"></a>

```typescript
public readonly outputPath: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#output_path File#output_path}.

---

##### `type`<sup>Required</sup> <a name="@cdktf/provider-archive.FileConfig.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#type File#type}.

---

##### `excludes`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.excludes"></a>

```typescript
public readonly excludes: string[];
```

- *Type:* `string`[]

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#excludes File#excludes}.

---

##### `id`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#id File#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `outputFileMode`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.outputFileMode"></a>

```typescript
public readonly outputFileMode: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#output_file_mode File#output_file_mode}.

---

##### `source`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.source"></a>

```typescript
public readonly source: FileSource[] | IResolvable;
```

- *Type:* [`@cdktf/provider-archive.FileSource`](#@cdktf/provider-archive.FileSource)[] | [`cdktf.IResolvable`](#cdktf.IResolvable)

source block.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#source File#source}

---

##### `sourceContent`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.sourceContent"></a>

```typescript
public readonly sourceContent: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#source_content File#source_content}.

---

##### `sourceContentFilename`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.sourceContentFilename"></a>

```typescript
public readonly sourceContentFilename: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#source_content_filename File#source_content_filename}.

---

##### `sourceDir`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.sourceDir"></a>

```typescript
public readonly sourceDir: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#source_dir File#source_dir}.

---

##### `sourceFile`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileConfig.property.sourceFile"></a>

```typescript
public readonly sourceFile: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#source_file File#source_file}.

---

### FileSource <a name="@cdktf/provider-archive.FileSource"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { FileSource } from '@cdktf/provider-archive'

const fileSource: FileSource = { ... }
```

##### `content`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSource.property.content"></a>

```typescript
public readonly content: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#content File#content}.

---

##### `filename`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSource.property.filename"></a>

```typescript
public readonly filename: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/archive/r/file#filename File#filename}.

---

## Classes <a name="Classes"></a>

### DataArchiveFileSourceList <a name="@cdktf/provider-archive.DataArchiveFileSourceList"></a>

#### Initializers <a name="@cdktf/provider-archive.DataArchiveFileSourceList.Initializer"></a>

```typescript
import { DataArchiveFileSourceList } from '@cdktf/provider-archive'

new DataArchiveFileSourceList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

##### `terraformResource`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceList.parameter.terraformResource"></a>

- *Type:* [`cdktf.IInterpolatingParent`](#cdktf.IInterpolatingParent)

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceList.parameter.terraformAttribute"></a>

- *Type:* `string`

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceList.parameter.wrapsSet"></a>

- *Type:* `boolean`

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods"></a>

##### `get` <a name="@cdktf/provider-archive.DataArchiveFileSourceList.get"></a>

```typescript
public get(index: number)
```

###### `index`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceList.parameter.index"></a>

- *Type:* `number`

the index of the item to return.

---


#### Properties <a name="Properties"></a>

##### `internalValue`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataArchiveFileSource[];
```

- *Type:* [`cdktf.IResolvable`](#cdktf.IResolvable) | [`@cdktf/provider-archive.DataArchiveFileSource`](#@cdktf/provider-archive.DataArchiveFileSource)[]

---


### DataArchiveFileSourceOutputReference <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference"></a>

#### Initializers <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.Initializer"></a>

```typescript
import { DataArchiveFileSourceOutputReference } from '@cdktf/provider-archive'

new DataArchiveFileSourceOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

##### `terraformResource`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.parameter.terraformResource"></a>

- *Type:* [`cdktf.IInterpolatingParent`](#cdktf.IInterpolatingParent)

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.parameter.terraformAttribute"></a>

- *Type:* `string`

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.parameter.complexObjectIndex"></a>

- *Type:* `number`

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.parameter.complexObjectIsFromSet"></a>

- *Type:* `boolean`

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---



#### Properties <a name="Properties"></a>

##### `contentInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.property.contentInput"></a>

```typescript
public readonly contentInput: string;
```

- *Type:* `string`

---

##### `filenameInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.property.filenameInput"></a>

```typescript
public readonly filenameInput: string;
```

- *Type:* `string`

---

##### `content`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.property.content"></a>

```typescript
public readonly content: string;
```

- *Type:* `string`

---

##### `filename`<sup>Required</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.property.filename"></a>

```typescript
public readonly filename: string;
```

- *Type:* `string`

---

##### `internalValue`<sup>Optional</sup> <a name="@cdktf/provider-archive.DataArchiveFileSourceOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataArchiveFileSource;
```

- *Type:* [`cdktf.IResolvable`](#cdktf.IResolvable) | [`@cdktf/provider-archive.DataArchiveFileSource`](#@cdktf/provider-archive.DataArchiveFileSource)

---


### FileSourceList <a name="@cdktf/provider-archive.FileSourceList"></a>

#### Initializers <a name="@cdktf/provider-archive.FileSourceList.Initializer"></a>

```typescript
import { FileSourceList } from '@cdktf/provider-archive'

new FileSourceList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

##### `terraformResource`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceList.parameter.terraformResource"></a>

- *Type:* [`cdktf.IInterpolatingParent`](#cdktf.IInterpolatingParent)

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceList.parameter.terraformAttribute"></a>

- *Type:* `string`

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceList.parameter.wrapsSet"></a>

- *Type:* `boolean`

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods"></a>

##### `get` <a name="@cdktf/provider-archive.FileSourceList.get"></a>

```typescript
public get(index: number)
```

###### `index`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceList.parameter.index"></a>

- *Type:* `number`

the index of the item to return.

---


#### Properties <a name="Properties"></a>

##### `internalValue`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileSourceList.property.internalValue"></a>

```typescript
public readonly internalValue: FileSource[] | IResolvable;
```

- *Type:* [`@cdktf/provider-archive.FileSource`](#@cdktf/provider-archive.FileSource)[] | [`cdktf.IResolvable`](#cdktf.IResolvable)

---


### FileSourceOutputReference <a name="@cdktf/provider-archive.FileSourceOutputReference"></a>

#### Initializers <a name="@cdktf/provider-archive.FileSourceOutputReference.Initializer"></a>

```typescript
import { FileSourceOutputReference } from '@cdktf/provider-archive'

new FileSourceOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

##### `terraformResource`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.parameter.terraformResource"></a>

- *Type:* [`cdktf.IInterpolatingParent`](#cdktf.IInterpolatingParent)

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.parameter.terraformAttribute"></a>

- *Type:* `string`

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.parameter.complexObjectIndex"></a>

- *Type:* `number`

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.parameter.complexObjectIsFromSet"></a>

- *Type:* `boolean`

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---



#### Properties <a name="Properties"></a>

##### `contentInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.property.contentInput"></a>

```typescript
public readonly contentInput: string;
```

- *Type:* `string`

---

##### `filenameInput`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.property.filenameInput"></a>

```typescript
public readonly filenameInput: string;
```

- *Type:* `string`

---

##### `content`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.property.content"></a>

```typescript
public readonly content: string;
```

- *Type:* `string`

---

##### `filename`<sup>Required</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.property.filename"></a>

```typescript
public readonly filename: string;
```

- *Type:* `string`

---

##### `internalValue`<sup>Optional</sup> <a name="@cdktf/provider-archive.FileSourceOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: FileSource | IResolvable;
```

- *Type:* [`@cdktf/provider-archive.FileSource`](#@cdktf/provider-archive.FileSource) | [`cdktf.IResolvable`](#cdktf.IResolvable)

---



