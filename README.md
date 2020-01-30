# material-ui-snippets

[![CircleCI](https://circleci.com/gh/vscodeshift/material-ui-snippets.svg?style=svg)](https://circleci.com/gh/vscodeshift/material-ui-snippets)
[![Coverage Status](https://codecov.io/gh/vscodeshift/material-ui-snippets/branch/master/graph/badge.svg)](https://codecov.io/gh/vscodeshift/material-ui-snippets)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/vscodeshift.material-ui-snippets)

snippets for Material-UI

# Snippets

<!-- snippets -->
### `mui-bottom-navigation-action`: Material-UI &lt;BottomNavigationAction&gt;

```
<BottomNavigationAction label="$1" value={$2} icon={$3} $0 />
```

### `mui-bottom-navigation`: Material-UI &lt;BottomNavigation&gt;

```
<BottomNavigation
  value={$1}
  onChange={$2}
  $3
>
  $0
<BottomNavigation>
```

### `mui-button-group-vertical`: Material-UI vertical &lt;ButtonGroup&gt;

```
<ButtonGroup orientation="vertical" variant="${1:outlined}" color="${2:primary}" aria-label="$3" $4>
  <Button>$5</Button>
  <Button>$6</Button>
  $0
</ButtonGroup>
```

### `mui-button-group`: Material-UI &lt;ButtonGroup&gt;

```
<ButtonGroup variant="${1:outlined}" color="${2:primary}" aria-label="$3" $4>
  <Button>$5</Button>
  <Button>$6</Button>
  $0
</ButtonGroup>
```

### `mui-button-text`: Material-UI text &lt;Button&gt;

```
<Button color="${1:primary}" $2>
  $0
</Button>
```

### `mui-button-with-icon`: Material-UI &lt;Button&gt; with icon and label

```
<Button
  variant="${1:contained}"
  color="${2:primary}"
  startIcon={$3}
  $4
>
  $0
</Button>
```

### `mui-button`: Material-UI &lt;Button&gt;

```
<Button variant="${1:contained}" color="${2:primary}" $3>
  $0
</Button>
```

### `mui-checkbox-label-placement`: Material-UI &lt;Checkbox&gt; with labelPlacement

#### Controlled

```
<FormControlLabel
  label="$1"
  labelPlacement="${2:start}"
  control={
    <Checkbox
      value="$3"
      checked={$4}
      onChange={$5}
      color="${6:primary}"
    />
  }
/>
```

#### Uncontrolled

```
<FormControlLabel
  label="$1"
  labelPlacement="${2:start}"
  control={
    <Checkbox
      value="$3"
      defaultChecked={$4}
      color="${5:primary}"
    />
  }
/>
```

### `mui-checkbox-label`: Material-UI &lt;Checkbox&gt; with &lt;FormControlLabel&gt;

#### Controlled

```
<FormControlLabel
  label="$1"
  control={
    <Checkbox
      value="$2"
      checked={$3}
      onChange={$4}
      color="${5:primary}"
    />
  }
/>
```

#### Uncontrolled

```
<FormControlLabel
  label="$1"
  control={
    <Checkbox
      value="$2"
      defaultChecked={$3}
      color="${4:primary}"
    />
  }
/>
```

### `mui-container`: Material-UI &lt;Container&gt;

```
<Container maxWidth="${1:sm}">
  $0
</Container>
```

### `mui-drawer-permanent`: Material-UI permanent &lt;Drawer&gt;

```
<Drawer
  variant="permanent"
  anchor="${1:left}"
  $2
>
  $0
</Drawer>
```

### `mui-drawer-persistent`: Material-UI persistent &lt;Drawer&gt;

```
<Drawer
  variant="persistent"
  anchor="${1:left}"
  open={$2}
  $3
>
  $0
</Drawer>
```

### `mui-drawer-temporary`: Material-UI temporary &lt;Drawer&gt;

```
<Drawer
  variant="temporary"
  anchor="${1:left}"
  open={$2}
  onClose={$3}
  $4
>
  $0
</Drawer>
```

### `mui-end-adornment`: Material-UI start &lt;InputAdornment&gt;

```
startAdornment={
  <InputAdornment position="start">
    $0
  </InputAdornment>
}
```

### `mui-form-control-group`: Material-UI &lt;FormControl&gt; with &lt;FormGroup&gt;

```
<FormControl component=${1:"fieldset"} $2>
  <FormLabel component=${3:"legend"}>$4</FormLabel>
  <FormGroup>
    $0
  </FormGroup>
  <FormHelperText>$5</FormHelperText>
</FormControl>
```

### `mui-form-control`: Material-UI &lt;FormControl&gt;

```
<FormControl $1>
  <FormLabel>$2</FormLabel>
  $0
  <FormHelperText>$3</FormHelperText>
</FormControl>
```

### `mui-grid-container-center`: Material-UI &lt;Grid container&gt; with centering

```
<Grid
  container
  spacing={${1:1}}
  direction="${2:row}"
  justify="${3:center}"
  alignItems="${4:center}"
  alignContent="${5:center}"
  wrap="${6:wrap}"
  $7
>
  $0
</Grid>
```

### `mui-grid-container-full`: Material-UI &lt;Grid container&gt; with all props

```
<Grid
  container
  spacing={${1:1}}
  direction="${2:row}"
  justify="${3:flex-start}"
  alignItems="${4:stretch}"
  alignContent="${5:stretch}"
  wrap="${6:wrap}"
  $7
>
  $0
</Grid>
```

### `mui-grid-container`: Material-UI &lt;Grid container&gt;

```
<Grid container spacing={${1:1}} $2>
  $0
</Grid>
```

### `mui-grid-list-subheader`: Material-UI GridList subheader

```
<GridListTile cols={${1:2}} style={{ height: 'auto' }}>
  <ListSubheader component="div">$0</ListSubheader>
</GridListTile>
```

### `mui-grid-list-tilebar`: Material-UI &lt;GridListTileBar&gt;

```
<GridListTileBar
  title=${1:""}
  subtitle=${2:""}
  actionIcon={
    <IconButton aria-label="$3" $4>
      $0
    </IconButton>
  }
/>
```

### `mui-icon-button`: Material-UI &lt;IconButton&gt;

```
<IconButton
  aria=label="$1"
  onClick={$2}
  $3
>
  $0
</IconButton>
```

### `mui-menu-item`: Material-UI &lt;MenuItem&gt;

```
<MenuItem onClick={$1} $2>$0</MenuItem>
```

### `mui-menu-popup-state`: Material-UI &lt;Menu&gt; for material-ui-popup-state

```
<Menu
  id="$1"
  keepMounted
  {...bindMenu(${2:popupState})}
  $3
>
  $0
</Menu>
```

### `mui-menu`: Material-UI &lt;Menu&gt;

```
<Menu
  id="$1"
  anchorEl={$2}
  keepMounted
  open={Boolean($2)}
  onClose={$3}
  $4
>
  $0
</Menu>
```

### `mui-radio-group`: Material-UI &lt;FormControl&gt; with &lt;RadioGroup&gt;

```
<FormControl component=${1:"fieldset"} $2>
  <FormLabel component=${3:"legend"}>$4</FormLabel>
  <RadioGroup aria-label="$5" name="$6" value={$7} onChange={$8}>
    $0
  </RadioGroup>
  <FormHelperText>$9</FormHelperText>
</FormControl>
```

### `mui-radio-label-placement`: Material-UI &lt;Radio&gt; with &lt;FormControlLabel&gt; with labelPlacement

```
<FormControlLabel value="$1" label="$2" labelPlacement="${3:start}" control={<Radio $0 />} />
```

### `mui-radio-label`: Material-UI &lt;Radio&gt; with &lt;FormControlLabel&gt;

```
<FormControlLabel value="$1" label="$2" control={<Radio $0 />} />
```

### `mui-select-item`: Material-UI &lt;MenuItem&gt; inside &lt;Select&gt;

```
<MenuItem value={$1} $2>$0</MenuItem>
```

### `mui-slider-continuous`: Material-UI &lt;Slider&gt; with continuous values

#### Controlled

```
<Slider
  value={$1}
  onChange={$2}
  aria-labelledby="$3"
  min={$4:0}
  max={$5:100}
  $0
/>
```

#### Uncontrolled

```
<Slider
  defaultValue={$1}
  aria-labelledby="$2"
  min={$3:0}
  max={$4:100}
  $0
/>
```

### `mui-slider-discrete`: Material-UI &lt;Slider&gt; with discrete values

#### Controlled

```
<Slider
  value={$1}
  onChange={$2}
  aria-labelledby="$3"
  step={$4:1}
  marks
  min={$5:0}
  max={$6:100}
  $0
/>
```

#### Uncontrolled

```
<Slider
  defaultValue={$1}
  aria-labelledby="$2"
  step={$3:1}
  marks
  min={$4:0}
  max={$5:100}
  $0
/>
```

### `mui-start-adornment`: Material-UI end &lt;InputAdornment&gt;

```
endAdornment={
  <InputAdornment position="end">
    $0
  </InputAdornment>
}
```

### `mui-switch-label-placement`: Material-UI &lt;Switch&gt; with &lt;FormControlLabel&gt; with labelPlacement

#### Controlled

```
<FormControlLabel
  label="$1"
  labelPlacement="${2:start}"
  control={
    <Switch
      value="$3"
      checked={$4}
      onChange={$5}
      $0
    />
  }
/>
```

#### Uncontrolled

```
<FormControlLabel
  label="$1"
  labelPlacement="${2:start}"
  control={
    <Switch
      value="$3"
      defaultChecked="$4"
      $0
    />
  }
/>
```

### `mui-switch-label`: Material-UI &lt;Switch&gt; with &lt;FormControlLabel&gt;

#### Controlled

```
<FormControlLabel
  label="$1"
  control={
    <Switch
      value="$2"
      checked={$3}
      onChange={$4}
      $0
    />
  }
/>
```

#### Uncontrolled

```
<FormControlLabel
  label="$1"
  control={
    <Switch
      value="$2"
      defaultChecked="$3"
      $0
    />
  }
/>
```

### `mui-switch`: Material-UI &lt;Switch&gt;

#### Controlled

```
<Switch
  value="$1"
  checked={$2}
  onChange={$3}
  inputProps={{ 'aria-label': '$4' }}
  $0
/>
```

#### Uncontrolled

```
<Switch
  value="$1"
  defaultChecked="$2"
  inputProps={{ 'aria-label': '$3' }}
  $0
/>
```

### `mui-text-field-select`: Material-UI &lt;TextField select&gt;

#### Controlled

```
<TextField
  id="$1"
  label="$2"
  select
  value={$3}
  onChange={$4}
  $5
>
  $0
</TextFIeld>
```

#### Uncontrolled

```
<TextField
  id="$1"
  label="$2"
  select
  defaultValue={$3}
  $4
>
  $0
</TextFIeld>
```

### `mui-text-field-variant`: Material-UI &lt;TextField&gt; with variant

#### Controlled

```
<TextField
  id="$1"
  label="$2"
  variant="${3:filled}"
  value={$4}
  onChange={$5}
  $0
/>
```

#### Uncontrolled

```
<TextField
  id="$1"
  label="$2"
  variant="${3:filled}"
  defaultValue={$4}
  $0
/>
```

### `mui-text-field`: Material-UI &lt;TextField&gt;

#### Controlled

```
<TextField
  id="$1"
  label="$2"
  value={$3}
  onChange={$4}
  $0
/>
```

#### Uncontrolled

```
<TextField
  id="$1"
  label="$2"
  defaultValue={$3}
  $0
/>
```
<!-- snippetsend -->
