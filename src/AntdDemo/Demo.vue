<template>
  <section>
    <Button type="primary">hello</Button>

    <Select style="width: 200px;">
      <Option value="jack">Jack</Option>
      <Option value="lucy">Lucy</Option>
    </Select>
  </section>
</template>

<script>
  import { Button, Select } from 'antd';

  const { Option } = Select;

  export default {
    components: {
      Button,
      Select,
      Option,
    },
  }
</script>
