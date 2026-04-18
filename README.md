# ABAP CDS File Icons

File icons for ABAP RAP development in Visual Studio Code. Designed for use with [ABAP Remote FS](https://marketplace.visualstudio.com/items?itemName=murbani.vscode-abap-remote-fs).

## Supported Object Types

| Icon | Abbr | Object Type | Extension |
|------|------|-------------|-----------|
| ![CL](#) | CL | Class | `*.clas.abap` |
| ![IF](#) | IF | Interface | `*.intf.abap` |
| ![PR](#) | PR | Program / Report | `*.prog.abap` |
| ![DS](#) | DS | CDS Data Definition | `*.ddls.asddls` |
| ![MX](#) | MX | Metadata Extension | `*.ddlx.asddlx` |
| ![BD](#) | BD | Behavior Definition | `*.bdef.asbdef` |
| ![SD](#) | SD | Service Definition | `*.srvd.asdsrvd` |
| ![SB](#) | SB | Service Binding | `*.srvb.asdsrvb` |
| ![AC](#) | AC | Access Control (DCL) | `*.dcls.asdcls` |
| ![TB](#) | TB | Database Table | `*.tabl.xml` |
| ![DE](#) | DE | Data Element | `*.dtel.xml` |
| ![DM](#) | DM | Domain | `*.doma.xml` |
| ![ST](#) | ST | Structure | `*.stru.xml` |
| ![TT](#) | TT | Table Type | `*.ttyp.xml` |
| ![VW](#) | VW | DDIC View | `*.view.xml` |
| ![LK](#) | LK | Lock Object | `*.enqu.xml` |
| ![FG](#) | FG | Function Group | `*.fugr.xml` |
| ![FM](#) | FM | Function Module | `*.func.abap` |
| ![NR](#) | NR | Number Range Object | `*.nrob.xml` |
| ![SH](#) | SH | Search Help | `*.sush.xml`, `*.suso.xml` |
| ![EI](#) | EI | Enhancement Implementation | `*.enho.xml` |
| ![ES](#) | ES | Enhancement Spot | `*.enhs.xml` |
| ![CD](#) | CD | Change Document | `*.chdo.xml` |
| ![AB](#) | AB | Generic ABAP | `*.abap` |

## Installation

Search for **ABAP CDS File Icons** in the VS Code Extensions panel.

After installation, activate the theme via **File > Preferences > File Icon Theme > ABAP CDS Icons**.

## Development

### Prerequisites

```bash
npm install -g @vscode/vsce
```

### Package

```bash
vsce package
```

### Publish

```bash
vsce publish
```

## License

[MIT](LICENSE)
