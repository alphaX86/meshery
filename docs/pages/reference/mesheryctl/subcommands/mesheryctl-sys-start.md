---
layout: default
title: mesheryctl system start
permalink: reference/mesheryctl/commands/subcommands/mesheryctl-system-start
type: reference
display-title: "false"
language: en
lang: en
categories: en
list: exclude
# image: /assets/img/platforms/brew.png
---

<!-- Copy this template to create individual doc pages for each mesheryctl commands -->

<!-- Name of the command -->
# mesheryctl system start

## Description

<!-- Basic usage of the command -->
<pre class="codeblock-pre">
  <div class="codeblock">
    <div class="clipboardjs">
  mesheryctl system start[flags]
    </div>
  </div>
</pre>

## Examples

<pre class="codeblock-pre">
  <div class="codeblock">
  {% for command_hash in site.data.mesheryctlcommands.lifecycle.system.start.command %}{% assign command = command_hash[1] %}
  # {{ command.description }}
  {{ command.usage }}
  {% endfor %}
  {% for flag_hash in site.data.mesheryctlcommands.lifecycle.system.start.flag %}{% assign flag = flag_hash[1] %}
  # {{ flag.description }}
  {{ flag.usage }}
  {% endfor %}
  </div>
</pre>
<br/>


<!-- Options/Flags available in this command -->
## Options

<pre class="codeblock-pre">
  <div class="codeblock">
    {% for flag_hash in site.data.mesheryctlcommands.lifecycle.system.start.flag %}{% assign flag = flag_hash[1] %}
    {{ flag.flag }} # {{ flag.description }}
    {% endfor %}
  </div>
</pre>
<br/>