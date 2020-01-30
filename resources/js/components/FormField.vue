<template>
    <default-field :field="field">
        <template slot="field">
            <span class="form-control form-plain-text text-80">
                {{ field.value }}
            </span>
        </template>
    </default-field>
</template>

<script>
import { FormField } from 'laravel-nova';

export default {
  mixins: [FormField]
};
</script>
