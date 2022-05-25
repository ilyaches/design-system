<template>
    <div>
        <h1>Button</h1>
        <h2>Default with icon</h2>
        <div class="component-bg">
            <c-button left-icon="add" width="140px" variant="solid"
                class="button-default focus-remove button-scale">Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button left-icon="add" width="140px" variant="solid" class="button-default focus-remove button-scale">Button&lt;/c-button>
            </span>
        </div>

        <h2>Default</h2>
        <div class="component-bg">
            <c-button width="140px" variant="solid" class="button-default focus-remove button-scale">Button
            </c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button width="140px" variant="solid" class="button-default focus-remove button-scale">Button&lt;/c-button>
            </span>
        </div>

        <h2>Outline with icon</h2>
        <div class="component-bg">
            <c-button left-icon="add" width="140px" class="button-outline focus-remove button-scale"
                variant="outline">Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button left-icon="add" width="140px" class="button-outline focus-remove button-scale" variant="outline">Button&lt;/c-button>
            </span>
        </div>

        <h2>Outline</h2>
        <div class="component-bg">
            <c-button width="140px" class="button-outline focus-remove button-scale" variant="outline">Button
            </c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button width="140px" class="button-outline focus-remove button-scale" variant="outline">Button&lt;/c-button>
            </span>
        </div>

        <h2>Small with icon</h2>
        <div class="component-bg">
            <c-button size="sm" left-icon="add" width="100px" class="button-default focus-remove button-scale"
                variant="solid">Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button size="sm" left-icon="add" width="100px" class="button-default focus-remove button-scale"
                variant="solid">Button&lt;/c-button>
            </span>
        </div>

        <h2>Small</h2>
        <div class="component-bg">
            <c-button size="sm" width="100px" class="button-default focus-remove button-scale" variant="solid">
                Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button size="sm" width="100px" class="button-default focus-remove button-scale" variant="solid">Button&lt;/c-button>
            </span>
        </div>

        <h2>Small outline with icon</h2>
        <div class="component-bg">
            <c-button size="sm" left-icon="add" width="100px" class="button-outline focus-remove button-scale"
                variant="outline">Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button size="sm" left-icon="add" width="100px" class="button-outline focus-remove button-scale" variant="outline">Button&lt;/c-button>
            </span>
        </div>

        <h2>Small outline</h2>
        <div class="component-bg">
            <c-button size="sm" width="100px" class="button-outline focus-remove button-scale" variant="outline">
                Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button size="sm" width="100px" class="button-outline focus-remove button-scale" variant="outline">Button&lt;/c-button>
            </span>
        </div>

        <h2>Ghost with icon</h2>
        <div class="component-bg">
            <c-button width="100px" left-icon="add" class="button-ghost focus-remove button-scale"
                variant="ghost">Button</c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button width="100px" left-icon="add" class="button-ghost focus-remove button-scale" variant="ghost">Button&lt;/c-button>
            </span>
        </div>

        <h2>Ghost</h2>
        <div class="component-bg">
            <c-button width="100px" class="button-ghost focus-remove button-scale" variant="ghost">Button
            </c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button width="100px" class="button-ghost focus-remove button-scale" variant="ghost">Button&lt;/c-button>
            </span>
        </div>

        <h2>Link</h2>
        <div class="component-bg">
            <c-button width="100px" class="button-link focus-remove button-scale" variant="link">Button
            </c-button>
        </div>
        <div class="code-bg">
            <span>
                &lt;c-button width="100px" class="button-link focus-remove button-scale" variant="link">Button&lt;/c-button>
            </span>
        </div>
    </div>
</template>



<script>
import { CButton } from "@chakra-ui/vue";

export default {
    components: {
        CButton
    }
}
</script>


